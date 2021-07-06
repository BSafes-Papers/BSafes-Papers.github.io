---
layout: default
title: 5. CREATING A POC SMURF IMPLEMENTATION  
parent: § Social Media User Relationship Framework (SMURF)  
grand_parent: Social Media 
nav_order: 50 
---
<style>
.dont-break-out {
  /* These are technically the same, but use both */
  overflow-wrap: break-word;
  word-wrap: break-word;

     -ms-word-break: break-all;
  /* This is the dangerous one in WebKit, as it breaks things wherever */
  word-break: break-all;
  /* Instead use this non-standard one: */
  word-break: break-word;
}

.youtube-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%;
}
.youtube-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

</style>

<div class="dont-break-out" markdown="1">

1. TOC
{:toc}

## 5. CREATING A POC SMURF IMPLEMENTATION
This section presents the data generation and analysis methodology for a PoC.

### 5.1 Data Generation
The data set used in this paper was generated from previous experiments conducted as part of the work presented in David et al. (2020). It involved the simulation of a range of normal user activity on Twitter, some of which include a variety of the activities listed below:

- ⇒ Power on and log in to the experimental VM
- ⇒ Launch the web browser (Google Chrome and Firefox were used)
- ⇒ Login to test user account on Twitter via the browser
- ⇒ Search for users to follow (publicly accessible accounts e.g. @bbcgoodfood)
- ⇒ Sending tweets (text, images, links)
- ⇒ Reply and retweet messages
- ⇒ Viewing and sending Direct Messages (DMs)
- ⇒ Sending photos via DM
- ⇒ Retweets via DM
- ⇒ Send follow requests to other test user account
- ⇒ Viewing and accepting follow requests
- ⇒ Updating the account privacy settings
- ⇒ Scrolling through the test user account timelines and that of its followers

### 5.2 Data Analysis
The data analysis for this paper was conducted in a Windows 10 desktop environment using the PoC framework - SMURF. This section discusses how individual components of the SMURF were used for data analysis; it includes code extracts with several lines removed for brevity. 

A graphical illustration of SMURF is shown in Figures 2 and 3. It shows the components that make up the framework and how they feed data into the core component enabling the generation of a report with the relevant information required by an investigator.

#### 5.2.1 Component: device_identifier
This component was used to retrieve the identifying information for the triage device on which SMURF was running. This includes the Vendor ID (VID) and Product ID (PID) of the device. 

This information is written to the report to account for the interaction between the triage device and the target device being investigated.


Extracts from device_id.py
![Extracts from device_id.py](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-extract-5-2-1.png)


#### 5.2.2 Component: predefined_paths
This component was written to support artefact recovery from Windows Registry. It contains known paths of interest in the SAM, SECURITY, SOFTWARE, SYSTEM, NTUSER.DAT and UsrClass.dat hives and was used as a global settings file for the registry parsers. 

The paths held in this component can be used to provide context to user activity in a live triage. For example, identifying applications (e.g. browsers) installed by the user, mounted devices (e.g. shared network drives used for sharing files on social media). See Appendix A.1 for extracts.

#### 5.2.3 Component: app_config
This component is made up of individual parsers for the registry hives. It is important to note that the SAM and SECURITY hives are locked and inaccessible when the device is powered on. This is because Windows locks the file and prevents read/write activity from any accounts other than the SYSTEM. To address this limitation, the parsers used the Python subprocess module to call the *reg.exe save hklm\x* command (e.g. reg.exe save hklm\sam). This was used to dump the SAM and SECURITY hives. The HARDWARE hive was also dumped to grab the current state of the system hardware information as this hive is volatile and is lost when the device is powered off.


![A “practitioner friendly” illustration of SMURF components and how data is fed into the main component](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-fig-2.png)
Figure 2: Part 1
A “practitioner friendly” illustration of SMURF components and how data is fed into the main component

The winreg module was used to access the Windows registry API in read-only mode to minimise any possible impact on the target device. See Appendix A.2 for extracts.

#### 5.2.4 Component: system_info
This component was used for the recovery of system generated artefacts from Prefetch and Event Logs. This was used to provide corroborating information on application installation and access times; and also to provide context to user activity.

This component was used to demonstrate the ability to use third party command-line interface (CLI) tools within SMURF. For example:

- ⇒ PECmd Zimmerman (2019) is a CLI tool that was used to process the Prefetch files and return the contents in JSON format. 

- ⇒ python-evt Ballenthin (2019), a Python parser for Windows event logs (postWindows XP), was used to process the Application and Security event logs. The output was saved as an XML file and a function was written to parse the XML file to display the content in an “easy to digest” format in the report. 

- ⇒ SysInternals tools Russinovich (2016, 2018) were used to recover additional/corroborating system related and generated artefacts such as processes, registered owner, system uptime etc.

The subprocess module was used to call these third party tools from the *system_info* component. See Appendix A.3 for extracts.


![A “practitioner friendly” illustration of SMURF components and how data is fed into the main component](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-fig-3.png)
Figure 3: Part 2
A “practitioner friendly” illustration of SMURF components and how data is fed into the main component

#### 5.2.5 Component: session_info
This component was used to recover artefacts from the browser session files. For this paper, two types of session related artefacts were recovered. Extracts can be found in Appendix A.4.

- I. sessionstore.mozlz4: this is used by Firefox to store session data. Artefacts from this file were recovered using a Python script derived from Blumenbach (2015)’s mozlz4a script.

- II. Current/Last Session; Current/Last Tabs: these are used by Google Chrome, and as implied by the file names, the window and tab activities of the user are stored here. When Chrome is running, these files are locked by the host and are inaccessible, so it was necessary to use the psutil module to programmatically terminate chrome.exe. The output was saved in text files for subsequent processing using RegEx.

#### 5.2.6 Component: browser_history
This component was used to recover artefacts related to user browser activity. It is also designed to be extensible, allowing for the recovery of artefacts from multiple browsers and for session information to be fed into the framework to support browser history artefacts. It calls third party tools such as *chromagnon* Bancel, Jean-Rémy (2015) which was used to parse the Chrome History file, and to facilitate the recovery of session artefacts. 

For the purposes of this paper, artefacts from Firefox and Chrome were analysed. See Appendix A.5 for extracts.

#### 5.2.7 Component: browser_cache
This component was used to recover data in the browser cache that can be used for the corroboration of other browser artefacts. 

The manual analysis conducted by David et al. (2020), observed and highlighted that content may be cached independent of user interaction. The cache returns a sizeable volume of data thus, for a live triage use case, this component focuses on the recovery of URL related cached content to reduce the amount of time and effort required to process cache information.

This component also demonstrates the extensibility and flexibility of SMURF. It calls third party tools such as *Hindsight* by Obsidian Forensics Benson (2019), which was used to facilitate the parsing of the browser cache artefacts. See Appendix A.6 for extracts.

#### 5.2.8 Component: smurf_main
This is the main component of the framework. It was used to collate, manage the data ingested from the artefacts from the other components.

It was designed to format the data recovered and to generate a HTML report that was used to display the results in an ‘easy to assimilate’ format for the investigators (see Appendix A.7 for the HTML template extracts).


Extracts from smurf_main.py
![Extracts from smurf_main.py](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-extract-5-2-7.png)
![](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-extract-5-2-7-2.png)

### 5.3 Method of Deployment
Being a collection of components, some of which call third party tools/utilities, a number of options were considered as possible methods of deployment. This was done to ensure:

- ⇒ good ethical conduct and compliance with the legal use of the third party tools (i.e. adherence to potential licence ramifications or legal implications); 

- ⇒ respect for the authors and their licences by using the tool in the way author consent implies.

Some of the utilities explored as a method of deployment can be used to bundle a python script and its dependencies into an executable file; however these were deemed impractical for the purposes of demonstrating the extensibility and adaptability of SMURF and ensuring that third party tools are used as intended as mentioned above. 

WinPython WinPython (2019) a free, portable scientific distribution of Python for Windows was deployed to a USB device and used to test the PoC in a live Windows 10 VM.

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/social-media/social-media-user-relationship-framework-1/">1. INTRODUCTION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-2/">2. LITERATURE REVIEW</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-3/">3. SMURF</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-4/">4. BUILDING THE SMURF FRAMEWORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-5/">5. CREATING A POC SMURF IMPLEMENTATION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-6/">6. CASE STUDY - SMURF ON TWITTER</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-7/">7. DISCUSSION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-8/">8. CONCLUSION AND FUTURE WORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-9/">REFERENCES</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-10/">A.</a></li></ul>

***

</div>

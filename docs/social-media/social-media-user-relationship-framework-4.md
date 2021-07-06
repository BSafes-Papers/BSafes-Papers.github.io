---
layout: default
title: 4. BUILDING THE SMURF FRAMEWORK 
parent: § Social Media User Relationship Framework (SMURF)  
grand_parent: Social Media 
nav_order: 40 
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

## 4. BUILDING THE SMURF FRAMEWORK
This section discusses at a high level, the theoretical aspects of SMURF. The intention was to build a linear, modular investigative tool, with the potential to extend and mature its functionality. SMURF’s modularity allows for the addition or exclusion of components based on the use case.

Figure 1 is a graphical representation of how SMURF works. The components used to achieve these are discussed in Section 5.

### 4.1 Capture
This stage involves recovering data from a live machine. As this is the stage that initiates interaction between the triage device and the target device, it was necessary to first programmatically record the triage device details, the date and time it was connected to the target device before proceeding with the data collection. 

The data collection at this stage focused on system generated and user generated artefacts (e.g. web browser artefacts).


![Figure 1: An illustration of how SMURF works](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-fig-1.png)
Figure 1: An illustration of how SMURF works

### 4.2 Identify
This stage involves segregating the data collected during the capture. The artefacts are grouped based on type and the location found. For example, if the data contains the social media platform name or an associated name, and it is a URL (type), put it in the “visited places group” for further processing.

### 4.3 Process

The artefacts recovered and grouped at the “Identify” stage are processed to highlight the type of activity that could have created them. For example, user account registration, viewing and sharing content etc. 

This stage also involves the use of pattern matching techniques as presented in David et al. (2020) to extract features of interest.

### 4.4 Present
The data from preceding stages feed into the “Present” stage. Here, the results from the processing stage are parsed and returned in a text based HTML report. Following the theme of a live triage, this report provides the investigator with a quick view of the data recovered, in a usable manner.

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/social-media/social-media-user-relationship-framework-1/">1. INTRODUCTION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-2/">2. LITERATURE REVIEW</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-3/">3. SMURF</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-4/">4. BUILDING THE SMURF FRAMEWORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-5/">5. CREATING A POC SMURF IMPLEMENTATION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-6/">6. CASE STUDY - SMURF ON TWITTER</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-7/">7. DISCUSSION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-8/">8. CONCLUSION AND FUTURE WORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-9/">REFERENCES</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-10/">A.</a></li></ul>

***

</div>

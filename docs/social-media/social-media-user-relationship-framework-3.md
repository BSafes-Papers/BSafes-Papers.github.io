---
layout: default
title: 3. SMURF
parent: § Social Media User Relationship Framework (SMURF)  
grand_parent: Social Media 
nav_order: 30 
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

## 3. SMURF
SMURF is a framework built from a collection of components, and designed for live triage investigations focused on user activity on social media in digital forensics. 

SMURF is a command-line interface (CLI) tool designed to automate the recovery of artefacts that can be used by investigators to infer and attribute actions to a user. 

This section discusses the characteristics and development of SMURF. It also discusses how SMURF can be used by investigators to effectively and quickly build and deploy triage tools during an investigation.

### 3.1 Framework Problem Definition
David et al. (2020) presented results from a manual analysis of user activity on Twitter. This was done as a “dead disk” forensic analysis and provided some examples of the type of artefacts that an investigator may expect to find on digital storage media where a user has engaged in activity on Twitter.

In some time sensitive cases, digital forensic investigators are required to perform a live triage in order to obtain actionable intelligence that will help save the life of an individual (e.g. missing person). In such instances, this immediate need for actionable intelligence takes precedence over a full disk analysis which can be conducted later.

SMURF intends to address the need for a generalisable, reusable, and adaptable technique for automated evidence recovery from a variety of usage scenarios, providing a reusable design with multiple levels of functionality. To do this, SMURF is designed for:

- I. use in a live triage investigation

- II. the furtherance of the automated recovery, categorising recovered artefacts based on possible usage scenarios and the enabling the attribution of actions or relationships to a user. 

- III. the provision of quick and usable information that would enable investigators define the initial stages of an investigation, generate new leads, and highlight possible areas of interest to be looked at during a detailed forensic analysis.

### 3.2 Framework Characteristics
The development process for SMURF involved considering the characteristics that would define its functionality. This includes determining the availability and location of artefacts of interest, determining the types of artefacts that can be used to provide context to user activity.

This process also includes understanding that certain types of artefacts such as the contents of communication (e.g. text, multimedia files) may not be readily available to view or accessible on disk as they may be in unallocated space. Thus, it may be necessary to recover and use other artefacts that could be used in making inferences about user activity.

It is also important to understand how these artefacts can be used to attribute actions and relationships to a user based on the amount and usefulness of the actionable intelligence SMURF provides an investigator. This will enable an investigator to understand the context of the artefact, how it came to be, and what possible usage scenario could have created it. It will also assist the investigator when making a judgement on how to proceed.

### 3.3 Framework Development
The limitations observed with the ability to recover artefacts from social media activity (Section 3.2, i.e. communications content in unallocated space) highlights the need to identify and define the artefacts that may be of interest during a triage investigation. 

Examples of these artefacts include browser history data such as presented in David et al. (2020) i.e. URLs, authentication credentials, session information, cached data etc. as well as system artefacts that provide context about the user accounts, programs and applications running on their digital storage media.

#### 3.3.1 Components
This stage of the framework development process involved identifying and defining the major parts that constitute the framework. It involved evaluating the artefacts recovered during the manual investigation of the disk image and determining whether the artefacts would provide quick, easy to assimilate information for an investigator during a live triage. 

The manual artefacts were subsequently categorised into context and case specific artefacts; then they were broken down into specific artefacts from which the framework components were derived. 

Examples include: 

- I. a component that recovers artefacts containing user account information, such as the number of user accounts on the computer, the user Security Identifier (SID), and logon/logoff information

- II. component for the recovery of user data from social media activity 

As SMURF is intended for live triage investigations, it was determined that a component would be required for logging the interaction between the deployment device and the target device in compliance with ACPO #2.

#### 3.3.2 Development Environment
This stage of the framework involved identifying a suitable programming language for the proof of concept (PoC). It also involved reviewing existing work with open source live triage tools to enable a gap analysis as part of this research. The gap analysis identified the capabilities of existing tools and how SMURF augments them.

The development environment setup is as follows: 

- ⇒ Windows 10 Education (Local Machine) 

- ⇒ Python 3 

- ⇒ PyCharm Professional Edition with Anaconda Plugin

**Scripting Individual Components** Each component of the framework (as described in Section 3.3.1) was scripted to recover specific artefacts. In addition to the artefact-specific components, a ‘core’ component was also scripted to collate the recovered artefacts, and present them in a HTML report for the investigator. This approach can be described as a *“practitioner friendly”* approach to automated evidence recovery in a live triage.

This process is described further in Section 4.2 where a graphical illustration of the components is presented.

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/social-media/social-media-user-relationship-framework-1/">1. INTRODUCTION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-2/">2. LITERATURE REVIEW</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-3/">3. SMURF</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-4/">4. BUILDING THE SMURF FRAMEWORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-5/">5. CREATING A POC SMURF IMPLEMENTATION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-6/">6. CASE STUDY - SMURF ON TWITTER</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-7/">7. DISCUSSION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-8/">8. CONCLUSION AND FUTURE WORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-9/">REFERENCES</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-10/">A.</a></li></ul>

***

</div>

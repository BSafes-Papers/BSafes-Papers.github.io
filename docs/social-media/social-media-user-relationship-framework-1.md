---
layout: default
title: 1. INTRODUCTION
parent: § Social Media User Relationship Framework (SMURF)  
grand_parent: Social Media 
nav_order: 10 
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

## 1. INTRODUCTION
Social media presents investigators with a plethora of useful digital evidence as shown by a range of criminal prosecutions and convictions as well as civil investigations with outcomes such as disciplinary measures. Thus, the timely recovery of these artefacts is considered of interest to investigators during a live triage.

Triage as a practice emerged in the field of medicine where it was used to assess hospital patients in order to establish the order of prioritization of treatment Robertson-Steel (2006). In digital forensics however, triage is a fast-growing practice with two streams; live and post-mortem triage.

In time sensitive investigations, the need to quickly obtain actionable intelligence, in a usable format from a live system Wiles and Reyes (2007) may take precedence over waiting to conduct a detailed forensic analysis. This paper proposes a proof of concept (PoC) framework for social media user attribution, to support investigators through the automated, targeted recovery artefacts from social media activity in a live triage.

This paper is focused on social media access through a web browser and aims to highlight the potential in using artefacts other than communication content to infer and contextualise user activity, and to attribute actions to a user. The proposed framework is intended to be applicable and generalisable to other triage investigations. The web browser(s) referenced in this paper is a demonstration for the framework.

### 1.1 Contribution
The key contributions of this paper are as follows:

- ⇒ the proposal of a PoC framework for live triage investigations involving social media 

- ⇒ defines a baseline for the artefacts of interest as a method for grouping social media artefacts based on the perceived user activity. This can be used in the prioritization of live triage data analysis 

- ⇒ a demonstration to test its applicability, generalisability and reliability through the identification of how SMURF can extend or complement existing triage tools

### 1.2 Paper Structure
The rest of this paper is structured as follows: related work is discussed in Section 2; SMURF is introduced in Section 3, discussing the problem definition, characteristics and development. Section 4 discusses the build process and how SMURF works. In Section 5, the PoC implementation is discussed including data generation, analysis and the PoC deployment. Section 6 presents a case study and reliability assessment. Section 7 contains the discussion, and Section 8 presents the conclusion and future work.

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/social-media/social-media-user-relationship-framework-1/">1. INTRODUCTION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-2/">2. LITERATURE REVIEW</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-3/">3. SMURF</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-4/">4. BUILDING THE SMURF FRAMEWORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-5/">5. CREATING A POC SMURF IMPLEMENTATION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-6/">6. CASE STUDY - SMURF ON TWITTER</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-7/">7. DISCUSSION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-8/">8. CONCLUSION AND FUTURE WORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-9/">REFERENCES</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-10/">A.</a></li></ul>

***

</div>

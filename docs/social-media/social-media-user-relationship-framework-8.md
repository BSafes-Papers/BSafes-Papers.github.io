---
layout: default
title: 8. CONCLUSION AND FUTURE WORK    
parent: § Social Media User Relationship Framework (SMURF)  
grand_parent: Social Media 
nav_order: 80 
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

## 8. CONCLUSION AND FUTURE WORK
This paper has demonstrated a PoC for a Social Media User Relationship Framework (SMURF). It has demonstrated through the results recovered the possibility of using SMURF in a live triage, to obtain quick, actionable intelligence that can be used to guide or progress an investigation.

It has been shown that communication content can be inferred from other sources such as the page title. This is useful in a live triage where it may not be possible to conduct an extensive keyword search or file carving.

For attribution, a user account can be linked to specific searches enabling an investigator to build a timeline of contact and subsequent activity with a person of interest or a victim.

This paper has presented a PoC with the potential for improvement and the extensibility of its existing functions. A number of opportunities for future work have been identified. These include implementing an automated process for the categorisation of potential artefacts of interest for example the categories discussed in Section 6 and extending the current functionality for other triage investigations.

It is important to note that additional cache data such as image files were not recovered as part of the framework however, in the event that image files are required as part of a live triage investigation, further work would be required to implement the recovery of image and video files using a range of techniques including known file hashes and skin tone detection. 

No machine learning (ML) or artificial intelligence (AI) techniques were implemented. This is an avenue for future work. With ML, the components can be trained to adapt to specific scenarios using pre-set case information thus improving and extending the current functionality

As mentioned in Section 6.2, SMURF (or elements of it) could be added as a plugin to Autopsy or other live triage tools. This will extend its current functionality and allow for the visualization of social media activity from browsers. 

As this demonstration was carried out on Windows 10, there is the potential for testing SMURF on other operating systems and on a variety of web browsers.

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/social-media/social-media-user-relationship-framework-1/">1. INTRODUCTION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-2/">2. LITERATURE REVIEW</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-3/">3. SMURF</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-4/">4. BUILDING THE SMURF FRAMEWORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-5/">5. CREATING A POC SMURF IMPLEMENTATION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-6/">6. CASE STUDY - SMURF ON TWITTER</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-7/">7. DISCUSSION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-8/">8. CONCLUSION AND FUTURE WORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-9/">REFERENCES</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-10/">A.</a></li></ul>

***

</div>

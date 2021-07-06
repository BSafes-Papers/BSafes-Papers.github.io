---
layout: default
title: 7. DISCUSSION   
parent: § Social Media User Relationship Framework (SMURF)  
grand_parent: Social Media 
nav_order: 70 
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

## 7. DISCUSSION
This paper was focused on developing and demonstrating a framework that can be used for the recovery of artefacts from social media activity during a live triage investigation and Twitter has been used as a case study to demonstrate the feasibility of deploying SMURF as a live triage investigative tool, as shown by the results presented in this paper. 

Communication was defined in Section 2, providing context to the type of artefacts that can be created and their recoverability. This was used as a means of defining what ‘communication content’ is in the context of this paper; thus creating a relationship between an action and the resultant artefact.

A baseline for defining the framework functionality based on perceived user activity and artefacts created was introduced as it was necessary to establish constraints for the purposes of testing the PoC. 

Using the weighting matrix described in Section 6, this paper has highlighted some possible use cases for Twitter activities and the type of artefacts that can be recovered and has shown that context is important when attributing actions to a user. For example, distinguishing use cases where:

- ⇒ a user logs in and interacts with others 

- ⇒ a user has an account but doesn’t login (at least not on the device being investigated) 

- ⇒ a user doesn’t have an account but frequents Twitter

Although the data set used in the creation of the framework can be said to be a subset of real world user activity, this paper demonstrates that it is possible to recover a wider range of artefacts created as a result of social media activity. This was confirmed by the results from Autopsy showing that the same category of artefacts were recoverable in both Autopsy and SMURF.

While discussing context, when it comes to the availability or non-availability of communication content, this paper demonstrated the possibility of recovering enough information to allow inferences to be drawn about the communication (see Figure 9); thus, allowing the investigator to identify and prioritize areas for further analysis. 

There are certain caveats to be aware of during the investigation of social media activity. For example, artefacts may exist as a result of background processes on the social media platform; a web browser’s caching mechanism and/or web storage of content the user has not interacted with; hence the need for context and corroboration when assessing relevance and reliability.

It is important to highlight that evidence from live triage may not necessarily be court bound but may end up being used as supporting evidence; thus, it is important to adhere to the relevant jurisdictional guidelines for handling evidence in a live triage.

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/social-media/social-media-user-relationship-framework-1/">1. INTRODUCTION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-2/">2. LITERATURE REVIEW</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-3/">3. SMURF</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-4/">4. BUILDING THE SMURF FRAMEWORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-5/">5. CREATING A POC SMURF IMPLEMENTATION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-6/">6. CASE STUDY - SMURF ON TWITTER</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-7/">7. DISCUSSION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-8/">8. CONCLUSION AND FUTURE WORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-9/">REFERENCES</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-10/">A.</a></li></ul>

***

</div>

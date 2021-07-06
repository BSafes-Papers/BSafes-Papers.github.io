---
layout: default
title: 2. LITERATURE REVIEW
parent: § Social Media User Relationship Framework (SMURF)  
grand_parent: Social Media 
nav_order: 20 
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

## 2. LITERATURE REVIEW
This section provides a background on related work in the investigation of social media activity, the rules and reliability of digital evidence, and live triage investigations. It discusses the challenges faced by practitioners in the course of investigating user social media activity, and acquiring digital evidence that can be used for the attribution of actions and relationships to a user.

### 2.1 Social Media and Digital Evidence
Social media provides an opportunity for users to connect with others of similar interests, form personal or business relationships, and to communicate in real time through sharing multimedia files, instant messaging, microblogging, advertising etc.

It also provides investigators with valuable evidence that can be used to connect a suspect (or suspects) to a criminal activity of interest or to other persons of interest.

Social media has been described by Zeng et al. (2010) as a distributed mode of generating, disseminating content and communication among communities. Its use as a source of digital evidence has been recognised as an area of interest Arshad et al. (2019) deserving of further research in the digital forensics community.

There have been a number of approaches taken by researchers and practitioners exploring social media activity. For example, Shaw et al. (2016) takes a network forensics approach, reviewing the vulnerabilities of social media platforms. Hubert (2014) presents techniques that can be applied to non-criminal investigations such as employee misconduct.

To understand social media communication within the context of this paper, it is necessary to define communication in a ‘traditional’ sense and how social media fits into the concept of communication. Communication, according to Dance (1967) has been described as “**the elicitation of a response from another,** without making a distinction between the interaction of animate and inanimate matter, or the interaction between humans and animals”. Littlejohn (1992) suggests that communication can be defined by “looking at **the conceptual components of the act**, for example, speech, symbols, interaction, and intention”.

These definitions outline, in a simplistic way, what communication entails i.e. “eliciting a response from another” through writing, speaking, the use of signs or symbols. It is also worthy to note that Littlejohn includes ‘intention’ as one of the conceptual components of the act of communicating.

Viewing these from a digital forensics perspective, communication on social media occurs through interactions/exchanges (action) that ‘elicit a response’ from other users, and these interactions tend to involve the use of textual, graphic, audio content amongst others. These exchanges to a degree, often reflect the ‘intent’ of the user initiating the interaction and may be used to form associations **(relationships)** on social media platforms.

This could be considered as useful evidence to digital forensics investigators. The content shared, when recovered can be submitted as digital evidence while the nature of the interaction when contextualised may be used to infer the user’s intent **(motive)** for example, the user may intend to provoke other users, commit a criminal act, or incite another user into committing a criminal act.

#### 2.1.1 Challenges Posed by Social Media Communication
Although it can be a valuable source of digital evidence, as with every technology, social media also presents challenges to investigators. Some of which include the use of proprietary data formats across supported devices, the type of artefacts written to disk, and the ability of a portion of the platform’s user community to engage in undesirable or unlawful activities Bello and DiBlasio (2013); Moore (2014); Select Committee on Communications (2014).

There has been several social media related prosecutions and convictions over the years, highlighting cases where social media has been used for activities such as trolling, murder, drug trafficking, and fraud Haroon and Carter (2010); Bello and DiBlasio (2013).

There is also the lack of standardisation Cusack and Son (2012) which often results in social media investigations being approached as a web browser focused investigation when the social media platform is accessed through a web browser. Self-contained social media applications may handle things differently but were not explored as they were deemed out of scope. It has been suggested that ACPO Guidelines can be used as a starting point when investigating social media activity in the UK.

Other challenges associated with the investigation of social media activity include communication content not being immediately available or accessible on disk David et al. (2020) without additional measures/efforts to retrieve it for example, the use of file carving scripts; there are also possible privacy implications as highlighted by Casey (2013) because some artefacts may contain information about unrelated users or activities.

#### 2.1.2 Requirements of Admissibility of Digital Evidence

Digital evidence has been defined in different ways depending on the context of the investigation (i.e. criminal or non-criminal). Casey (2004) defines digital evidence as *“data stored or transmitted using a computer, which supports or refutes a theory on how an event occurred”*; thus addressing the critical elements of a crime such as determining the intent of a suspect.

Mukasey et al. (2008) defines digital evidence as “*information or data of investigative value that is stored on, received or transmitted by a computer* ”; highlighting the role of digital evidence - its **“investigative value”** in criminal (or non-criminal) proceedings

Digital evidence is known to exhibit a number of characteristics e.g.:

- ⇒ Latency: the evidence must be processed in order to derive meaningful and usable data from it. 

- ⇒ Fidelity: the original evidence is not necessarily required. A copy of the original would suffice provided that the copying process does not invalidate the evidence. 

- ⇒ Volatility: digital evidence is at risk of intentional or unintentional alteration or deletion. Intentional changes may be an attempt by an individual to corrupt and invalidate the evidence McKemmish (2008) however, this can be addressed by maintaining an audit trail and a comprehensive log of the evidence recovery process.

In order to be considered valuable to an investigation, and to be admissible in a court of law, digital evidence needs to meet certain requirements which include being relevant to the case, reliable, authentic, complete (i.e. paints an understandable, full picture), believable and the recovery method must be repeatable and should produce the same results when conducted by an independent third party ACPO (2012).

These requirements complement the characteristics of digital evidence and guide its admissibility in court. It is important to note that there may be circumstances where changes to digital evidence in the course of an investigation is unavoidable; this can be managed by maintaining a comprehensive record of the interactions between the investigator and the target device and also the possible implications of those interactions.

### 2.2 Live Triage Investigations
Triage, historically has been in practice in the medical field and has been defined as *“the process of quickly examining patients who are taken to a hospital in order to decide which ones are the most seriously ill and must be treated first”* Cambridge University Press (2019). In digital forensics however, this definition can be used to describe two scenarios: an on-site/live triage or an off-site/post-mortem triage, depending on the type of investigation. Post-mortem triage is out of scope for this paper, for more information, see Garfinkel (2013); Jusas et al. (2017); Parsonage (2009); Roussev and Quates (2012).

Live (on-site) triage is a technique used by investigators to quickly retrieve actionable intelligence at a crime scene. It is implemented in time sensitive investigations such as kidnapping, missing persons; where there is an imminent threat to life; the use of encryption on a device; the need to extract and preserve volatile artefacts Bashir and Khan (2013) or the practicality of seizing a device.

Live triage is appropriate when the requirement for actionable intelligence outweighs the need to perform a lab-based, detailed forensic analysis on all potential sources of digital evidence discovered at a crime scene Wiles and Reyes (2007). The data recovered during a live triage can be used to guide the investigation by highlighting possible areas or persons of interest prior to a full forensic analysis of the digital storage media.

Existing research has proposed a number of techniques in the use of live triage in digital forensics investigations Gielen and Bolzoni (2014); Montasari (2016). These highlight live triage as a viable means of recovering intelligence that can be used to generate new leads and to assess the severity of a crime. The Computer Forensic Field Triage Process Model (CFFTPM) developed by Rogers et al. (2006) can be applied to a wide spectrum of investigations and is considered a foundation for modelling the live triage process. It is focused on on-site analysis of digital devices, to obtain information that can be used during the “search and execution” stage of the investigation or during a suspect’s interview. CFFTPM highlights the need to consider live triage as part of the digital forensics process.

The CFFTPM is not automated and is designed to be used by competent users. This requirement for examiner competency presents some challenges as additional resources may be expended on-site where the on-site investigation takes priority over existing cases Hitchcock et al. (2016), resulting in the creation of backlogs in the forensic lab as existing cases may need to be put on hold.

Hitchcock et al. however, in the Digital Field Triage Model (DFT) proposed that providing non-specialists with training on the skills required to supplement/support investigators and analysts on-site would help digital forensics units maximize resources and would also provide the information required during a live triage. This will ensure that analysts required in the lab are able to focus on lab-based work.

Cantrell et al. (2012); Cantrell and Dampier (2012) in the Digital Triage Process Model, also addressed the challenges of appropriately managing resources and the utilization of non-digital forensics specialists during live triage investigations by introducing and implementing semiautomated steps in the proposed process model. Semi-automation, it was argued, would make it easier for non-specialists to use; speed up the live triage process and make it possible for these processes to be scripted into a case-specific framework.

There are concerns around the use of live triage during investigations, specifically highlighting the possibility of data being written to the device being investigated. This is often dependent on the type of investigation. For example, during an incident response investigation, the objective is usually business continuity and ensuring that compromised systems are returned to a ‘good working state’ thus, creating files or writing to the target device is not often considered a problem Gielen and Bolzoni (2014).

During digital forensics investigations, the state of digital data is to remain unmodified where possible. Thus, in compliance with the relevant jurisdictional guidance and best practice, (e.g., ACPO Principle #2 as UK Guidance), all actions taken during a live triage including any possible impact must be documented and justified.

There are also concerns that a live triage may overlook pertinent evidence Casey (2013) however, this can be addressed by conducting a detailed forensic analysis of the device, building on the evidence recovered during the live triage. The detailed analysis may be conducted on-site or in the lab as appropriate.

In addition to the on-going research into the use of and applicability of live triage processes in digital forensics, further work is required to capture and address how triage tools can be used to:

- ⇒ supplement the limitations of existing tools and processes. 

- ⇒ manage targeted capture of specific volatile or case-based artefacts that can provide investigators with actionable intelligence.

### 2.3 Digital Evidence: Challenges
Digital evidence aims to link an offender to a crime or to exonerate a suspect. A number of factors however, pose a challenge to the recovery and use of digital evidence. For example, differences in operating systems, applications and storage methods; the use of concealment and cryptographic techniques DFRWS (2001); the complexity of digital devices 7safe (2014); TWGECSI (2001); the volume of data to be analysed ACPO (2012); data compression and the storage capacity of the digital devices McKemmish (2008); Sommer (1999); spoliation techniques Marcella and Menendez (2007).

Evidence from user Internet activity may change with little or no notice for example, changes to the browser data storage format (e.g. proprietary compression format) and the type of data stored (e.g. cookies, history) could influence the type of data available for recovery. This often means that it takes longer to understand and decode the data in order to extract meaningful information from it.

Marcella and Menendez (2007) suggests reviewing and assessing new technologies from an offender’s perspective in order to understand how it can be used to hinder an investigation. This is because technology often ends up being used in a manner that deviates from its original purpose. Encryption and evidence eliminating tools are widely available, often for free on the Internet and can be used to attempt to evade detection or prosecution.

### 2.4 The Reliability of Digital Evidence

In a generic sense, reliability has been defined as *“the quality of being able to be trusted or believed because of working or behaving well”* Cambridge University Press (2019).

Digital evidence could be user or system generated David et al. (2020) thus when determining its reliability, it is important to assess how trustworthy it is. This is because a number of system activities outside the control of the user may create artefacts that appear related to a case but may not be for example, background processes such as web browser caching.

Casey (2011) suggests that an effective way of assessing the reliability of digital evidence is to focus on the evidence itself (e.g. checking the evidence for signs of tampering/damage), rather than the process through which it was created.

Due to the nature of live triage investigations, where repeated access to a target device is not advisable, reliability can be assessed by:

- ⇒ logging and detailed documentation of the recovery process. 

- ⇒ how believable the evidence is; 

- ⇒ and how accurately such evidence can be correlated, corroborated and attributed to specific events. For example, artefact ‘*A*’ infers that the user ‘*Bob*’ added user ‘*Chuck*’ as a friend and has visited ‘Chuck’s’ profile ‘*X* ’ times; this inference is supported by JSON and cache artefacts which provide context and imply that ‘*Bob*’ and ‘*Chuck*’ have a social relationship.

#### 2.4.1 Relationship Attribution
Attribution in digital forensics is used to show a link between a suspect to the artefacts found on a digital device. In the context of this paper, relationship attribution is aimed at determining the degree to which a specific artefacts can be attributed to a specific event, using the artefacts recovered during a live triage.

This includes leveraging corroborating artefacts such as browser cached content, system generated artefacts etc. David et al. (2020) to show the connection between a user and social media activity or social relationships and associations. This would facilitate the prompt identification of persons of interest to an investigation prior to a detailed forensic analysis.

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/social-media/social-media-user-relationship-framework-1/">1. INTRODUCTION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-2/">2. LITERATURE REVIEW</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-3/">3. SMURF</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-4/">4. BUILDING THE SMURF FRAMEWORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-5/">5. CREATING A POC SMURF IMPLEMENTATION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-6/">6. CASE STUDY - SMURF ON TWITTER</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-7/">7. DISCUSSION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-8/">8. CONCLUSION AND FUTURE WORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-9/">REFERENCES</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-10/">A.</a></li></ul>

***

</div>

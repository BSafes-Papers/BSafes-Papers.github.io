---
layout: default
title:  6. CASE STUDY - SMURF ON TWITTER  
parent: § Social Media User Relationship Framework (SMURF)  
grand_parent: Social Media 
nav_order: 60 
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

## 6. CASE STUDY: SMURF ON TWITTER
This section discusses the framework testing process, using Twitter as a case study. The results discussed in this section are grouped based on potential user activity. The weighting scale used to determine the feasibility of SMURF is also discussed in this section.

### 6.1 Twitter as a Case Study
Twitter is a very popular, real-time information network with a global user base. It has been described as *“a service for friends, family and coworkers to communicate and stay connected through the exchange of quick, frequent messages. People post Tweets, which may contain photos, videos, links and text. These messages are posted to your profile, sent to your followers, and are searchable on Twitter search”* Twitter Help Center (2019).

Twitter in its FAQs for new users, provides a description of how the platform can be used. This information was used as a guidance to extrapolate the basic activities that can be carried out on Twitter. These activities were placed into categories and the weighting scale shown in Figure 4 was derived from the analysis conducted in David et al. (2020).

In the context of a live triage investigation, the following is proposed:

- ⇒ **Strongly expect to find:** these are a range of artefacts that should generally be available to the investigator e.g. username, email address.

- ⇒ **May expect to find:** these are a range of artefacts that may often be available but not always e.g. login/logout activity, profile IDs of other users. 

- ⇒ **Corroborates other artefacts:** these are artefacts that validates previously recovered artefacts e.g. search parameters in a URL. 

- ⇒ **Needs to be contextualized:** this refers to any artefact that could be interpreted to mean different things and thus needs to be put in context of the previously recovered artefacts to verify its relevance to the case e.g. the user’s email address, email addresses of other users. 

- ⇒ **Requires corroboration:** this refers to any artefact that could mean something else and cannot be validated on its own. It needs to be supported by existing artefacts (e.g., communication content, text extracts, images).

![Figure 4: An illustration of the weighting scale](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-fig-4.png)
Figure 4: An illustration of the weighting scale

It is important to note that there may be overlaps when weighting the availability and relevance of artefacts recovered during a live triage investigation. For example, an investigator **may expect** to find the username of another user but would need to **corroborate** that information and put it in **context** to determine if it occurred as a result of direct user interaction or background processes on the social media platform.

#### 6.1.1 Registration/Authentication Activities
Users can access Twitter in a ‘read-only’ mode if they are not registered or logged in i.e. they are able to view content but cannot respond or interact with other users. In order to get the full benefits of the platform, a registered account is required.

Creating an account allows a user to personalise the account by amending the account settings to allow or restrict the public from viewing tweets; and adding profile photos and banners.

Figure 5 shows the range of artefacts associated with user registration/authentication on Twitter as recovered by SMURF as part of the first stage of the framework testing. The results indicate that there is a strong possibility of recovering artefacts such as the email address that was used for account registration.

Subsequent to that, URLs indicating login/logout activity can also be recovered and used to infer user account authentication activity.

There are other artefacts that may be used to support account activity. These include finding the usernames, profile names, user/profile IDs for other users. This may occur during the registration process where Twitter suggests people the user may like to follow.

![Figure 5: User registration/authentication arte- fact weighting](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-fig-5.png)
Figure 5: User registration/authentication arte- fact weighting

In the context of user activity, to infer/confirm possible account ownership, **‘strongly expect to find’** provides stronger evidence to validate the assumption. Table 1 shows the possible locations of these types of artefacts from Firefox and Google Chrome.


Table 1: Possible locations of registration/au- thentication artefacts
![Table 1: Possible locations of registration/au- thentication artefacts](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-table-1.png)

#### 6.1.2 Search and View Contents
As mentioned in Section 6.1.1, it is possible for users who are not logged in or registered to search for and view content in Twitter. This may be through typing in a Twitter URL with the *@handle* of a Twitter user e.g. twitter.com/ joebloggs or through a search engine e.g. “joe bloggs twitter”.

The second stage of the framework testing involved the identification and recovery of artefacts that can be used to infer ‘search and view’ activities. This applies to both registered and unregistered users; the main difference being the availability of artefacts indicating that the user has a Twitter account for example, the presence of the artefacts described in Section 6.1.1.

Using the weighting matrix, the PoC was used to recover artefacts such as user/profile names and IDs in the **‘strongly expect to find’** category. Other artefacts that can be used to build context were recovered in the **‘may expect to find’** category. For example, where a Twitter user profile has been searched for by email address; the search parameters (may expect to find) can be used to contextualise the profile ID **(strongly expect to find**) and thus the profile visit/view.

Regular Expressions (RegEx) were used at this stage to parse the output files from the framework components to extract artefacts inferring a range of search and view activities that occurred on Twitter during the experiments. Table 2 shows the possible locations of these types of artefacts from Firefox and Google Chrome.

![Figure 6: User search and view artefact weighting](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-fig-6.png)
Figure 6: User search and view artefact weighting

Table 2: Possible locations of artefacts inferring search and view activity
![Table 2: Possible locations of artefacts inferring search and view activity](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-table-2.png)

#### 6.1.3 Share Content
Twitter is used for content dissemination through “Tweeting” or “Retweeting” content - images, videos, text, and/or audio. As part of content sharing, users may also choose to communicate privately by exchanging direct messages (DMs). 

Content exchanged on Twitter (tweets, retweets, DMs) may be accompanied by hashtags to highlight trending i.e. currently popular topics; the keyword(s) referencing the topic is prefixed with the hash symbol (#) for example, #fitness, #freebies, #LatestNews.

Social media communication in the context of this paper has been described in Section 2.1 as the messages exchanged between two (or more) users, which may contain text, audio, video or image files. 

As discussed in Section 2.1.1 some of the aforementioned may not be readily available or accessible on disk during a live triage investigation thus, it may be necessary to use other artefacts to build a picture of the user’s activity.

SMURF was used to search for evidence of these activities to determine the reliability of the weighting matrix applied to the manual analysis of the artefacts presented in David et al. (2020). 

Figure 7 shows the range of user artefacts that may be used to infer content sharing on Twitter. For example, user/profile names and IDs, in addition to URLs parameters such as file names can be used in conjunction with page titles and login/logout URLs to infer a user was logged and possibly shared the file. 

The framework did not focus on or attempt the recovery of the exact contents of communication as the goal of a live triage is the timely and efficient provision of reliable intelligence, for the intended audience (e.g. investigators), in a usable and easy to understand format. However, the recovered artefacts will need to be corroborated.

It is important to note that non-registered users cannot share but are able to view publicly available content (Section 6.1.2) so **context** is necessary in order to draw inferences. 

Table 3 shows the possible locations of these types of artefacts from Firefox and Google Chrome.

Table 3: Possible locations of artefacts inferring content sharing activity
![Table 3: Possible locations of artefacts inferring content sharing activity](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-table-3.png)

#### 6.1.4 Associations/Relationships
On Twitter, users can choose to subscribe and be notified of another user’s tweets. This is described as “following” Twitter Help Center (2019) and is designed as a two-way process where users follow each other. However, there are instances where one user does not reciprocate for example, a corporate entity would have several, perhaps thousands of followers but will not follow all its followers.


![Figure 7: User shared content artefact weighting](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-fig-7.png)
Figure 7: User shared content artefact weighting

"Followership" may be used to determine a user’s interests, infer associations and relationships.

Figure 8 shows a range of artefacts recovered by SMURF and their weighting. These artefacts can be used to draw inferences about a user’s associations and by extension relationships on Twitter.

In order to determine the relationship(s) between users on Twitter, it is important to put the evidence inferring contact in context. This is because it is possible to form associations without a direct relationship. Examples include but are not limited to where a user has connections with or follows Government or Commercial entities with a Twitter profile; following celebrity fan pages or profiles or following other users with similar interests (photography, hiking etc.).


![Figure 8: User association/relationship attribu- tion](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-fig-8.png)
Figure 8: User association/relationship attribu- tion

It may also be possible to use Twitter search and query parameters to aid the attribution of associations and relationships to a user. This may be useful in highlighting where particular user profiles were searched for and then added as a social connection.

Table 4 shows the possible locations of these types of artefacts from Firefox and Google Chrome.

Table 4: Possible locations of artefacts inferring associations/relationships
![Table 4: Possible locations of artefacts inferring associations/relationships](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-table-4.png)

### 6.2 SMURF: Assessing Artefact Reliability with AUTOPSY®
As part of assessing the reliability of the artefacts recovered by the framework, and to highlight its contributions to the digital forensics community, SMURF was tested against Autopsy® 4.15.0 Carrier (2020); an open source, peer reviewed, in-use digital forensics tool. 

Autopsy® is a digital forensics platform and graphical interface to The Sleuth Kit® and other digital forensics tools Carrier (2020). It has a broad range of features including “Communications Visualization” which provides a consolidated view of events of interest and allows the investigator to visualize communication based on commonly used accounts and the timeframe of an event of interest.

The process consists of the following activities: 

- ⇒ Download Autopsy 4.15.0 from GitHub 

- ⇒ Install Autopsy and create a new case 

- ⇒ Add the experimental VM as a “Data Source”

- ⇒ Select and run relevant ingest modules (“Recent Activity”, “Keyword Search”) 

- ⇒ Review results 

A comparison of the artefacts inferring user activities as recovered by SMURF and the web browser activities recovered by Autopsy showed that SMURF was able to capture these activities as shown in Figures 9 and 10.

An attempt was made to visualise social media activities through the “Communications Visualization” feature, based on the Twitter URLs recovered by Autopsy however, it appears that web history visualisation is currently not supported although it works well with accounts found in the Data Source e.g. email accounts (PST, EML, MBOX), call logs and accounts from mobile devices. These were out of scope and not explored further.

In May 2020, Brian Carrier through Basis Technology Basis Technology (2020) offered free Autopsy training. The feedback from the digital forensics community evidenced the value of the tool. It was suggested that users can leverage the extensibility of Autopsy by adding plugins to the tool.

![Figure 9: Social media URL artefacts recovered by SMURF](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-fig-9.png)
Figure 9: Social media URL artefacts recovered by SMURF

![Figure 10: Social media URL artefacts recovered by Autopsy](https://statics.bsafes.com/images/papers/social-media-user-relationship-framework-fig-10.png)
Figure 10: Social media URL artefacts recovered by Autopsy

This research has identified the possibility of enhancing the “Communications Visualization” feature in Autopsy to allow the identification and inclusion of social media artefacts from web browsers as discussed in Section 8.

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/social-media/social-media-user-relationship-framework-1/">1. INTRODUCTION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-2/">2. LITERATURE REVIEW</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-3/">3. SMURF</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-4/">4. BUILDING THE SMURF FRAMEWORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-5/">5. CREATING A POC SMURF IMPLEMENTATION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-6/">6. CASE STUDY - SMURF ON TWITTER</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-7/">7. DISCUSSION</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-8/">8. CONCLUSION AND FUTURE WORK</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-9/">REFERENCES</a></li><li> <a href="/docs/social-media/social-media-user-relationship-framework-10/">A.</a></li></ul>

***

</div>

---
layout: default
title: 9 Result Interpretation and Reporting      
parent: §  NESCOR Guide to Penetration Testing for Electric Utilities 
grand_parent: Infrastructure 
nav_order: 90 
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
</style>

<div class="dont-break-out" markdown="1">
1. TOC
{:toc}

## 9 Result Interpretation and Reporting
As penetration-testing tasks are completed, vulnerabilities should be found and documented. When a vulnerability is found, testers should briefly document the relative risk that the particular vulnerability presents to the in-scope system and the business in general and a brief note of how that vulnerability could be mitigated. These initial impressions of risk and mitigation are important to document at that time since the tester is usually most immersed in that vulnerability at the time when it is discovered. Upon completion of all penetration test tasks, theses initial impressions should be reviewed and adjusted based on other vulnerabilities found in the system. For instance, a penetration tester may find two vulnerabilities that he initially believes are low risk vulnerabilities to the system. However upon completion of all penetration testing tasks, the tester may realize that an attacker could leverage both low level vulnerabilities to create a new higher risk vulnerability. This analysis should be done once all testing tasks are completed and the final report is being generated. At the time of final report generation, each vulnerability should be fully documented and mitigation recommendations should be expanded to be applicable with the testers latest, more complete understanding of the system.

The final report should, at a minimum, include the following sections: 

- Executive Summary - a brief 1-2 page section discussing the overarching root causes for the vulnerabilities and high level business strategies to address these root causes. 

- Introduction – a short section describing the goals of the tests, components that were in and out of scope, any special restrictions on the tests, and the team involved with the testing. 

- Methodology – a short section of the report focuses on the technical reasons for the test as well as the methodology used. 

- Findings and Recommendations – this section of the report is traditionally the longest, most detailed, and highly technical. This is the core of the report for future use and reference. This section may also discuss the likelihood and impact of each vulnerability within the context of the proposed or existing deployment. 

- Conclusion – a section similar to the executive summary but at a more technical depth summarizing the major findings and recommendations. This section should also discuss any major questions or goals of the assessment such as the team’s recommendations of a go no-go purchase of a product.

</div>

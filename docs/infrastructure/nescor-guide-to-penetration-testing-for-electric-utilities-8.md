---
layout: default
title: 8 End-to-End Penetration Test Analysis      
parent: §  NESCOR Guide to Penetration Testing for Electric Utilities 
grand_parent: Infrastructure 
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
</style>

<div class="dont-break-out" markdown="1">
1. TOC
{:toc}

## 8 End-to-End Penetration Test Analysis
The final task in any penetration test should be a gap analysis of communications that span the entire system. This should include a review of input and output from external systems that may not be in scope for this assessment. For instance, when testing an AMI meter system, a tester might have performed tests on all components from the meter to the headend. However this final end-to-end task should ensure that all possible inputs from external systems to in-scope systems have been tested and evaluated as possible attack angles, such as an out-of-scope backend systems dependent on data from the in-scope system. Also, malicious data from out-of-scope systems that is accepted and used by in-scope systems, such as public key infrastructure (PKI) servers, should be considered in this part of the assessment. Penetration testers should also identity if any vulnerabilities found later in the testing process affect components tested earlier or by other testing teams.

***
#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-1/">1 Introduction</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-2/">2 Penetration Test Scoping</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-3/">3 Target System Setup</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-4/">4 Embedded Device Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-5/">5 Network Communications Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-6/">6 Server OS Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-7/">7 Server Application Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-8/">8 End-to-End Penetration Test Analysis</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-9/">9 Result Interpretation and Reporting</a></li></ul>

***

</div>

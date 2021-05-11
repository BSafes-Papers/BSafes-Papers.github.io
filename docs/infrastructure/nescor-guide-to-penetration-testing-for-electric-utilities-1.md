---
layout: default
title: 1 Introduction 
parent: §  NESCOR Guide to Penetration Testing for Electric Utilities 
grand_parent: Infrastructure 
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
</style>

<div class="dont-break-out" markdown="1">
1. TOC
{:toc}

## 1 Introduction
This document was created for electric utilities to use in their security assessment of Smart Grid and other energy management systems. Smart Grid security assessments can be broken into several categories. This document focuses only on penetration testing and attempts to help utilities break down the complex process of penetration testing. Penetration testing is a specialized form of hands-on assessment where the testing team takes on the role of the attacker and tries to find and exploit vulnerabilities in systems and devices. Testers use the same methodology that attackers use to identify vulnerabilities in a system, which is usually a semi-blind exploratory interaction with the system looking for both previously-known and previously-unknown vulnerabilities in the target system. Once a vulnerability is found, the testers attempt to exploit the flaw to gain a foothold in the system and begin the process again to discover additional, lower level vulnerabilities that weren’t previously exposed. Penetration testing is distinguished from vulnerability assessment techniques by the fact that they test for a depth of vulnerabilities instead of simply breadth, focus on discovering both known and unknown vulnerabilities, and provide the testing team with a better understanding of a particular vulnerability’s risk to the business through the vulnerability’s exploitation.

This document is intended to help electric utility security teams plan their penetration testing activities and understand rough levels of effort they should expect when performing these types of tests. When electric utilities do not have staff with the appropriate understanding or skill to perform penetration testing in-house, this document can be used in their services procurement processes to understand potential scope, plan budgets, create RFP documents, and evaluate the responses from firms offering penetration-testing services.

This document breaks the process of penetration testing into logical tasks. These tasks are organized into logical categories based on the skill set of the testing team, each category represented by major sections in this document. Not all penetration testers have the skill set to perform all of the tasks. In most cases, the testing team will be made up of at least two individuals, each with unique but (hopefully) somewhat overlapping skill sets. Because of the nature of penetration testing, the tasks in this document are high level and intended to break the overall penetration test into logical components that can be assigned to testing team members to be completed in a systematic manner. **This document does not contain detailed, tool specific, step-by-step procedures for each task, but provides high-level descriptions of how a task is performed and the overall goals for each task in a Penetration Test.**

Results of penetration testing tasks are not expected to be fully repeatable or comparable from one utility to another utility, or from one testing team to another testing team. While all vulnerabilities found by the penetration testing team should be repeatable and verifiable by other organizations when given details of the vulnerability, the results of each penetration test is highly dependent on the skill set of the testing team, and the discovery of those vulnerabilities will vary from testing team to testing team. Because of these factors, the results of these penetration-testing tasks are not intended to be used by regulatory bodies or shared outside of the utility, with the exception of sharing these results with the respective vendors to have the discovered vulnerabilities addressed.

***
#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-1/">1 Introduction</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-2/">2 Penetration Test Scoping</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-3/">3 Target System Setup</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-4/">4 Embedded Device Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-5/">5 Network Communications Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-6/">6 Server OS Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-7/">7 Server Application Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-8/">8 End-to-End Penetration Test Analysis</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-9/">9 Result Interpretation and Reporting</a></li></ul>

***
</div>

---
layout: default
title: §  NESCOR Guide to Penetration Testing for Electric Utilities 
parent: Infrastructure 
has_children: true
nav_order: 986030000 
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
This is the mobile-friendly web version of the [original article](https://smartgrid.epri.com/doc/NESCORGuidetoPenetrationTestingforElectricUtilities-v3-Final.pdf).

![NESCOR Guide to Penetration Testing for Electric Utilities](https://statics.bsafes.com/images/papers/NESCORGuidetoPenetrationTestingforElectricUtilities-v3-Final-58.png)

# NESCOR Guide to Penetration Testing for Electric Utilities  
{: .no_toc }
## Version 3 
{: .no_toc }

## National Electric Sector Cybersecurity Organization Resource (NESCOR) 
{: .no_toc }

1. TOC
{:toc}

## DISCLAIMER OF WARRANTIES AND LIMITATION OF LIABILITIES
THIS DOCUMENT WAS PREPARED BY THE ORGANIZATION(S) NAMED BELOW AS AN ACCOUNT OF WORK SPONSORED OR COSPONSORED BY THE ELECTRIC POWER RESEARCH INSTITUTE, INC. (EPRI). NEITHER EPRI, NOR ANY MEMBER OF EPRI, ANY COSPONSOR, THE ORGANIZATION(S) BELOW, NOR ANY PERSON ACTING ON BEHALF OF ANY OF THEM: 

> (A) MAKES ANY WARRANTY OR REPRESENTATION WHATSOEVER, EXPRESS OR IMPLIED, (I) WITH RESPECT TO THE USE OF ANY INFORMATION, APPARATUS, METHOD, PROCESS, OR SIMILAR ITEM DISCLOSED IN THIS DOCUMENT, INCLUDING MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE, OR (II) THAT SUCH USE DOES NOT INFRINGE ON OR INTERFERE WITH PRIVATELY OWNED RIGHTS, INCLUDING ANY PARTY'S INTELLECTUAL PROPERTY, OR (III) THAT THIS DOCUMENT IS SUITABLE TO ANY PARTICULAR USER'S CIRCUMSTANCE; OR 

> (B) ASSUMES RESPONSIBILITY FOR ANY DAMAGES OR OTHER LIABILITY WHATSOEVER (INCLUDING ANY CONSEQUENTIAL DAMAGES, EVEN IF EPRI OR ANY EPRI REPRESENTATIVE HAS BEEN ADVISED OF THE POSSIBILITY OF SUCH DAMAGES) RESULTING FROM YOUR SELECTION OR USE OF THIS DOCUMENT OR ANY INFORMATION, APPARATUS, METHOD, PROCESS, OR SIMILAR ITEM DISCLOSED IN THIS DOCUMENT.

REFERENCE HEREIN TO ANY SPECIFIC COMMERCIAL PRODUCT, PROCESS, OR SERVICE BY ITS TRADE NAME, TRADEMARK, MANUFACTURER, OR OTHERWISE, DOES NOT NECESSARILY CONSTITUTE OR IMPLY ITS ENDORSEMENT, RECOMMENDATION, OR FAVORING BY EPRI.

THIS REPORT WAS PREPARED AS AN ACCOUNT OF WORK SPONSORED BY AN AGENCY OF THE UNITED STATES GOVERNMENT. NEITHER THE UNITED STATES GOVERNMENT NOR ANY AGENCY THEREOF, NOR ANY OF THEIR EMPLOYEES, MAKES ANY WARRANTY, EXPRESS OR IMPLIED, OR ASSUMES ANY LEGAL LIABILITY OR RESPONSIBILITY FOR THE ACCURACY, COMPLETENESS, OR USEFULNESS OF ANY INFORMATION, APPARATUS, PRODUCT, OR PROCESS DISCLOSED, OR REPRESENTS THAT ITS USE WOULD NOT INFRINGE PRIVATELY OWNED RIGHTS. REFERENCE HEREIN TO ANY SPECIFIC COMMERCIAL PRODUCT, PROCESS, OR SERVICE BY TRADE NAME, TRADEMARK, MANUFACTURER, OR OTHERWISE DOES NOT NECESSARILY CONSTITUTE OR IMPLY ITS ENDORSEMENT, RECOMMENDATION, OR FAVORING BY THE UNITED STATES GOVERNMENT OR ANY AGENCY THEREOF. THE VIEWS AND OPINIONS OF AUTHORS EXPRESSED HEREIN DO NOT NECESSARILY STATE OR REFLECT THOSE OF THE UNITED STATES GOVERNMENT OR ANY AGENCY THEREOF.

**Primary Author:**
Justin Searle, Utilisec

**Contributers:**
Galen Rasche, EPRI
Andrew Wright, N-Dimension Solutions
Scott Dinnage, N-Dimension Solutions

**Reviewers:**
NESCOR Team 3 Members and Volunteers
Annabelle Lee, EPRI

The research was paid for by the Department of Energy (DOE) under the NESCOR grant.

**Program Manager**
A. Lee

## Abstract

This security test plan template was created by the National Electric Sector Cybersecurity Organization Resource (NESCOR) to provide guidance to electric utilities on how to perform penetration tests on Smart Grid systems. Penetration testing is one of the many different types of assessments utilities can perform to assess their overall security posture. While NESCOR recommends that utilities engage in all other forms of security assessment, NESCOR created this document to help utilities plan and organize their AMI penetration testing efforts. For a list of other types of Smart Grid security assessments, please see NESCOR’s whitepaper titled “Guide to Smart Grid Assessments.” This document covers penetration test plans for Smart Grid systems in general with specific guidance for Advanced Metering Infrastrucgure (AMI), Wide-Area Monitoring, Protection, and Control (WAMPAC), and Home Area Network (HAN). Additional guidance for other Smart Grid product domains are expected to be added in later revisions of this document. For more information on this or other NESCOR documents, see the NESCOR’s website at www.smartgrid.epri.com/NESCOR.aspx

The objective of the NESCOR project is to establish an organization that has the knowledge and capacity to enhance the effort of the National Electric Sector Cybersecurity Organization (NESCO) by providing technical assessments of power system and cybersecurity standards to meet power system security requirements; provide recommendations for threats and vulnerabilities, and participate in testing emerging security technologies in labs and pilot projects.

Certain commercial entities, equipment, or materials may be identified in this document in order to describe an experimental procedure or concept adequately. Such identification is not intended to imply recommendation or endorsement by NESCOR, nor is it intended to imply that the entities, materials, or equipment are necessarily the best available for the purpose.

## Table of Contents
-  Introduction

- 2 Penetration Test Scoping 

- 3 Target System Setup

 - 3.1 Advanced Metering Infrastructure (AMI)

 - 3.2 Demand Response (DR)

 - 3.3 Distributed Energy Resources (DER)

 - 3.4 Distribution Grid Management (DGM)

 - 3.5 Electric Transportation (ET)

 - 3.6 Wide Area Monitoring, Protection, and Control (WAMPAC)

- 4 Embedded Device Penetration Tasks

 - 4.1 Electronic Component Analysis

 - 4.2 Field Technician Interface Analysis

 - 4.3 Firmware Binary Analysis

- 5 Network Communications Penetration Tasks

 - 5.1 RF Packet Analysis

 - 5.2 Network Protocol Analysis

- 6 Server OS Penetration Tasks

 - 6.1 Information Gathering

 - 6.2 Vulnerability Analysis

 - 6.3 Server OS Exploitation

- 7 Server Application Penetration Tasks

 - 7.1 Application Mapping

 - 7.2 Application Discovery

 - 7.3 Application Exploitation

- 8 End-to-End Penetration Test Analysis

- 9 Result Interpretation and Reporting

</div>

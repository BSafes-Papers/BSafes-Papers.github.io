---
layout: default
title: 2 Penetration Test Scoping 
parent: §  NESCOR Guide to Penetration Testing for Electric Utilities 
grand_parent: Infrastructure 
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
</style>

<div class="dont-break-out" markdown="1">
1. TOC
{:toc}

## 2 Penetration Test Scoping
Penetration testing should be performed on a periodic basis depending on the criticality of the targeted system. This can be performed as a broad penetration test encompassing several control systems (such as an entire testing or staging control network), a targeted penetration test with a restricted scope of a single control system (management server to its controlled devices), or to test a single component of a larger system, such as a historian or a reclosure. NESCOR recommends performing this type of assessment in testing or staging environments on an annual basis or after any major systems upgrades or changes to the systems in question.

Penetration tests should start with a review of the target architecture to help the testing team gain a deeper knowledge of the target system. This will help the testing team understand the intended functionality of the targeted system, its expected security posture from an architectural perspective, and the security risks that a vulnerability could pose to the organization. This is best performed through interviews with knowledgeable experts from both the product’s vendor and the utility or asset owner deploying the target system. 

Each penetration-testing task listed in this document contains an estimated level of effort, a task description, and a task goal. The level of effort for each task assumes a single target. For example, if a task involves analyzing dataset for cryptographic keys and is labeled “medium” effort, this signifies that the analysis of each distinct dataset should be calculated as a separate medium level effort. The analysis of multiple datasets could aggregate to a “medium” or “high” level of effort depending on the exact relative nature of those datasets. 

The following table was used to estimate the number of hours an **experienced tester** of the applicable skill set would take to complete each task:


<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="middle">

				<p align="center"><strong>Level &nbsp;of &nbsp;Effort</strong></p>
			</td>
			<td valign="middle">

				<p align="center"><strong>Number &nbsp;of &nbsp;Hours</strong></p>
			</td>
		</tr>
		<tr>
			<td valign="middle">

				<p align="center">Low</p>
			</td>
			<td valign="middle">

				<p align="center">1-&shy;4</p>
			</td>
		</tr>
		<tr>
			<td valign="middle">

				<p align="center">Medium</p>
			</td>
			<td valign="middle">

				<p align="center">5-&shy;16</p>
			</td>
		</tr>
		<tr>
			<td valign="middle">

				<p align="center">High</p>
			</td>
			<td valign="middle">

				<p align="center">17-&shy;40</p>
			</td>
		</tr>
		<tr>
			<td valign="middle">

				<p align="center">Extremely &nbsp;High</p>
			</td>
			<td valign="middle">

				<p align="center">41+</p>
			</td>
		</tr>
	</tbody>
</table>


The penetration-testing tasks included in this document were created to be used generically on all types of Smart Grid and energy management systems. Therefore, individual penetration-testing tasks may or may not apply depending on the specific system being tested. The testing team that is performing the tasks should determine which tests are applicable to accomplish their goals.

Figure 1 demonstrates how the following sections of this document interrelate to each other and when they are initiated in a typical penetration test. This diagram shows the overall process flow of a typical penetration test as described in this document. Each box represents a major section in this document and shows which sections need to be performed in serial and which sections can be performed in parallel.

Figure 2a: Typical Penetration Testing Process

All penetration tests should start with proper planning and scoping of the engagement. Once that is complete, the penetration testing tasks can be broken into the four distinct task categories displayed in Figure 2a. Each of these task categories also requires different skill sets from the testing team. If there is sufficient staff, these four penetration task categories can be performed in parallel. Once these tasks are completed, the team should perform a gap analysis to verify all desired tests have been performed and all goals met. Finally, the team should generate a report documenting their findings, interpret these findings in the context of the utility’s deployment, and develop recommendations to resolve or mitigate these vulnerabilities.

The color difference of these four penetration task categories in Figure 2a represents the relative likelihood that a utility should consider performing these tasks. These recommendations are based a combination of trends that NESCOR has seen in the industry and the level of expertise needed to perform these tests. To some degree, this also represents the relative risk target systems represent to the utility, as compromise of the control servers are generally considered a higher risk than the compromise of a single embedded field device or its network communications.

The colors in Figure 2.a can be interpreted as:

- Green: Tasks that should be performed most frequently, require the most basic of penetration testing skill, and can often be performed by internal security teams.

- Yellow: Tasks that are commonly performed and require moderate penetration testing skill.

- Orange: Tasks that are occasionally performed but may require higher levels of expertise.
 
- Red: Tasks that are infrequently performed and require highly specialized skills not often found in-house.

These colors are used in the diagrams presented in each major task category throughout the rest of this document. 

Each penetration task category in this document provides an overview of tasks that could be performed in any given penetration test. Penetration test planning should consider these lists of tasks and determine which tasks are appropriate to meet their desired goals of the penetration test. Some tests may include all tasks, other tests may only include tasks from one testing category, and other tests may include a small percentage of tasks from multiple testing categories. Any number of factors could drive these decisions, but the most common reasons for excluding a task from the assessment is budgetary restrictions, lack of applicability of a particular task, or unjustifiable risk to system or device. 

Each test category lists the types of tools needed for the tasks in that category. This list should not be considered prescriptive or complete, but rather a short sampling of tools to help point testing teams in the right direction. The tools needed will vary between individual testers, systems being tested and will change over time. Needed tools should be determined and assembled before testing begins.

</div>

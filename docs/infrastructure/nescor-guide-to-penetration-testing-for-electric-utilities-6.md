---
layout: default
title: 6 Server OS Penetration Tasks    
parent: §  NESCOR Guide to Penetration Testing for Electric Utilities 
grand_parent: Infrastructure 
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
</style>

<div class="dont-break-out" markdown="1">
1. TOC
{:toc}

## 6 Server OS Penetration Tasks
This section pertains to the testing of the operating system of the control servers. This follows more traditional network-based vulnerability assessment of the windows, unix, and linux based systems, such as the identification of missing security patches, insecure configurations, or presence of insecure services. The overarching goal is to identify and exploit un-patched vulnerabilities to gain access to the control server. The following table maps specific components that should be considered for each Smart Grid product domain.

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td rowspan="2" style="width: 14%;" valign="top">AMI
				<br>
				<br>
				<br>
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Headend &nbsp;servers &nbsp;(often &nbsp;several &nbsp;servers &nbsp;make &nbsp;up &nbsp;the &nbsp;&ldquo;headend&rdquo;)
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">The &nbsp;MDMS.
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="4" style="width: 14%;" valign="bottom">DR
				<br>
				<br>
				<br>
				<br>
				<br>
				<br>
				<br>
				<br>
				<br>
				<br>
			</td>
			<td valign="bottom">

				<p align="center">●</p>
			</td>
			<td valign="bottom">DRAS
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Gateway
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">BAS
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">DCU &nbsp;may &nbsp;run &nbsp;an &nbsp;OS
				<br>
			</td>
		</tr>
		<tr>
			<td valign="middle">DER
				<br>
			</td>
			<td valign="middle">

				<p align="center">●</p>
			</td>
			<td valign="middle">DER &nbsp;Management &nbsp;Server
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="2" style="width: 14%;" valign="bottom">DGM
				<br>
				<br>
				<br>
				<br>
			</td>
			<td valign="bottom">

				<p align="center">●</p>
			</td>
			<td valign="bottom">Management &nbsp;servers &nbsp;for &nbsp;each &nbsp;vendor&rsquo;s &nbsp;DGM &nbsp;devices
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">DGM &nbsp;Server
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="2" style="width: 14%;" valign="bottom">ET
				<br>
				<br>
				<br>
				<br>
			</td>
			<td valign="bottom">

				<p align="center">●</p>
			</td>
			<td valign="bottom">EV &nbsp;management &nbsp;server
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Gateway &nbsp;may &nbsp;run &nbsp;an &nbsp;OS
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="4" style="width: 14%;" valign="top">WAMPAC
				<br>
				<br>
				<br>
				<br>
				<br>
				<br>
				<br>
				<br>
				<br>
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Servers &nbsp;hosting &nbsp;WAMPAC &nbsp;applications
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">PDCs &nbsp;with &nbsp;operating &nbsp;systems
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">WAMPAC &nbsp;datastore &nbsp;applications
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">WAMPAC &nbsp;software &nbsp;installed &nbsp;on &nbsp;commodity &nbsp;operating &nbsp;systems.
				<br>
			</td>
		</tr>
	</tbody>
</table>


Figure 6a below shows the overall process flow of the task sub-categories in this section. The figure shows the three task sub-categories must be performed in series. As in previous diagrams in this document, the colors represent the recommended likelihood that a utility should consider performing these task sub-categories, and the relative level of expertise required.


Figure 6a: Server OS Subcategory Flow

Each subcategory below will include a similar diagram depicting the process flow and recommended likelihood to perform for each task. 

**Suggested Tools:**

- Standard network vulnerability assessment and penetration testing tools such as found on the BackTrack distribution 

- Guidance documents such as the Penetration Testing Standard (PTES)

### 6.1 Information Gathering

#### 6.1.1 DNS Interrogation

***Level of Effort:*** Low 

***Task Description:*** Use tools to attempt zone transfers and perform queries from target Domain Name Service (DNS) servers. 

***Task Goal:*** Identify targets, verify ownership, and detect anomalies.

#### 6.1.2 Port Scanning 

***Level of Effort:*** Low 

***Task Description:*** Use tools that send requests to possible application layer services (such as scanning TCP and UDP ports to discover services like HTTP and SSH). 

***Task Goal:*** Identify all listening services and possible firewall rules.

#### 6.1.3 Service Fingerprinting

***Level of Effort:*** Low

***Task Description:*** Use tools to examine listening services.

***Task Goal:*** Identify the nature and function of all listening services.

#### 6.1.4 SNMP Enumeration

***Level of Effort:*** Low

***Task Description:*** Use tools to attempt to examine SNMP services.

***Task Goal:*** Identify insecure SNMP services, extract information about the endpoints, and identify vulnerabilities that allow attackers to reconfigure endpoints.

#### 6.1.5 Packet Sniffing

***Level of Effort:*** Low

***Task Description:*** Capture various samples of network communications.

***Task Goal:*** Collect samples for later analysis.

### 6.2 Vulnerability Analysis

Figure 6.2a: OS Vulnerability Analysis Task Flow

#### 6.2.1 Unauthenticated Vulnerability Scanning

***Level of Effort:*** Medium

***Task Description:*** Use automated tools without credentials to identify known vulnerabilities in network services and their respective systems.

***Task Goal:*** Identify vulnerabilities in the operating system and the network services

#### 6.2.2 Authenticated Vulnerability Scanning

***Level of Effort:*** Medium

***Task Description:*** Use automated tools that use valid credentials to authenticate to systems and identify known vulnerabilities with installed software.

***Task Goal:*** Identify vulnerabilities in the operating system and installed software.

#### 6.2.3 Vulnerability Validation

***Level of Effort:*** Medium

***Task Description:*** Manually validate findings from automated tools where possible. Merge and combine findings where applicable.

***Task Goal:*** Consolidate findings and remove any false positive findings that you identify.

#### 6.2.4 Packet Capture Analysis

***Level of Effort:*** Low to Medium

***Task Description:*** Examine network traffic samples and look for protocols with known vulnerabilities such as session hijacking, weak authentication, or weak/no cryptographic protections.

***Task Goal:*** Identify vulnerabilities in network protocols and network communications.

### 6.3 Server OS Exploitation

Figure 6.3a: Server OS Exploitation Task Flow

#### 6.3.1 Identify Attack Avenues

***Level of Effort:*** Medium

***Task Description:*** Review all findings and outputs from previous tasks and identify plausible attacks that have a moderate chance of success. Prioritize these possible attacks by likelihood and the tester’s ability to execute them.

***Task Goal:*** Organize and plan next steps.

#### 6.3.2 Vulnerability Exploitation 

**Level of Effort:** Low to Medium 

***Task Description:*** Create proof of concept attacks to demonstrate the feasibility and business risk created by the discovered vulnerabilities. Once a vulnerability has been exploited, attempt to pivot and identify additional vulnerabilities to exploit. 

***Task Goal:*** Validate the assumed business risk created by the identified vulnerabilities and identify additional targets of opportunity.

#### 6.3.3 Post Exploitation

***Level of Effort:*** Low to Medium

***Task Description:*** Remove any code, data, or configurations that were added to the system as a part of the assessment.

***Task Goal:*** Return the systems to their pre-assessment state.


</div>

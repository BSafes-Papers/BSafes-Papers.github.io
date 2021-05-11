---
layout: default
title: 5 Network Communications Penetration Tasks   
parent: §  NESCOR Guide to Penetration Testing for Electric Utilities 
grand_parent: Infrastructure 
nav_order: 50 
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

## 5 Network Communications Penetration Tasks
This section pertains to the testing of network communications for the smart grid systems, such as field area networks. Primary targets include wireless medium, network protocols, network segmentation controls, etc. The overarching goal is to identify vulnerabilities that allow an attacker to control network traffic or to subvert a device through protocol manipulation. The following table will help map specific communications channels that should be considered for each Smart Grid product domain

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top">

				<p align="justify">AMI</p>
			</td>
			<td valign="top">

				<p align="justify">● &nbsp; &nbsp;Communications between Meter and aggregator&nbsp;</p>

				<p align="justify">● &nbsp; &nbsp;Communications between Aggregator and headend&nbsp;</p>

				<p align="justify">● Communications between Meter and headend in direct communication architectures&nbsp;</p>

				<p align="justify">● &nbsp; &nbsp;Communications between Headend and other systems such as the MDMS</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DR</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications between Energy resource and DCU&nbsp;</p>

				<p align="justify">● Communications between DCU and gateway&nbsp;</p>

				<p align="justify">● Communications between Energy resource and BAS&nbsp;</p>

				<p align="justify">● Communications between BAS and gateway&nbsp;</p>

				<p align="justify">● Communications between Energy resource and gateway&nbsp;</p>

				<p align="justify">● Other channels between the gateway and DRAS</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DER</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications between the managed generation and storage devices and the Customer Energy Management System&nbsp;</p>

				<p align="justify">● Communications between the DER Management Server and the managed generation and storage devices&nbsp;</p>

				<p align="justify">● Communications between the DER Management Server and other upstream servers that are dependent on its DER data</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DGM</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications between DGM field devices and their management servers&nbsp;</p>

				<p align="justify">● Communications to and from the DGM servers</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">ET</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications between EV and EVSE&nbsp;</p>

				<p align="justify">● Communications between EVSE and gateway&nbsp;</p>

				<p align="justify">● Communications between EVSE and EVSE&nbsp;</p>

				<p align="justify">● Communications between Meter and gateway&nbsp;</p>

				<p align="justify">● Communications between Meter and meter&nbsp;</p>

				<p align="justify">● Communications between Gateway and EV management server</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">WAMPAC</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications between Phasor management server and PMU&nbsp;</p>

				<p align="justify">● Communications between PMU and PDC&nbsp;</p>

				<p align="justify">● Communications between PDC and WAMPAC Application&nbsp;</p>

				<p align="justify">● Communications between PDC and Phasor Gateway&nbsp;</p>

				<p align="justify">● Any WAMPAC application that exchanges synchrophasor data with other systems&nbsp;</p>

				<p align="justify">● Any other communication channel between WAMPAC components&nbsp;</p>

				<p align="justify">● Communication with GPS satellites should also be tested, because core functionality in PMUs depend on accurate clock information from GPS.</p>
			</td>
		</tr>
	</tbody>
</table>


Figure 5a below shows the overall process flow of the task sub-categories in this section. The figure shows the two task sub-categories may be performed in parallel. As in previous diagrams in this document, the colors represent the recommended likelihood that a utility should consider performing these task sub-categories, and the relative level of expertise required.

![Figure 5a: Network Communications Subcategory Flow](https://statics.bsafes.com/images/papers/nescor-guide-to-penetration-testing-for-electric-utilities-fig-5a.png)
Figure 5a: Network Communications Subcategory Flow

Each subcategory below includes a similar diagram depicting the process flow and recommended likelihood to perform for each task.

**Suggested Tools:**
- Traffic capture and protocol decoder software such as Wireshark or tcpdump
- Hardware network taps
- Man-in-the-Middle tools such as Ettercap
- Protocol fuzzing tools such as Sulley
- Network packet generation such as Scapy
- Universal radio analysis kit, such as USRP2 with GNU Radio

### 5.1 RF Packet Analysis
This subcategory of penetration tasks focuses on the analysis of lower-layer RF communications such as frequency hopping, modulation, multiplexing, and data encoding in the Physical Layer and Medium Access Control Layer (PHY/MAC) of the Open Systems Interconnection (OSI) model. 

It is usually assumed that network traffic can be extracted from captured RF communications. As a result, utilities often choose not to perform these sub-tasks and often skip to the next Network Protocol Analysis subcategory of tasks. However, some utilities may find this task subcategory useful to determine the level of effort it would take for an attacker to capture and decode their RF network traffic, especially when the utility knows of security weaknesses in the higher layer network protocols. For entities interested in this type of analysis, consider the following suggestions in each Smart Grid product domain.

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top">

				<p align="justify">AMI</p>
			</td>
			<td valign="top">

				<p align="justify">● Wireless communications between meters in the NAN. For AMI meters in the United States, this is usually proprietary to each vendor, often using unlicensed bands which vary for each country (such as 900 MHz ISM band spectrum in the US)&nbsp;</p>

				<p align="justify">● These tests also pertain to cellular communications in the WAN</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DR</p>
			</td>
			<td valign="top">

				<p align="justify">● Wireless communications are seen usually between the energy resources and the gateway (including other possible intermediate devices of DCU and BAS), often leveraging IEEE 802.15.4 or Zigbee&nbsp;</p>

				<p align="justify">● The communication channel between the gateway and the DRAS doesn&rsquo;t often use ISM band communications, but may occasionally use cellular technologies</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DER</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications between the managed generation and storage devices and a gateway device on transit to the DER Management Server&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp;○ Often using IEEE 802.15.4 or Zigbee&nbsp;</p>

				<p align="justify">● Communications between the managed generation and storage devices and a gateway device on transit to the Customer Energy Management System&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; ○ Often using IEEE 802.15.4 or Zigbee</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DGM</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications between the DGM devices and a gateway device on transit to the DER Management Server&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Many DGM devices are starting to connect to the AMI network or directly connecting to a cellular backhaul&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ In some cases DGM devices use other wireless technologies to connect to the nearest substation</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">ET</p>
			</td>
			<td valign="top">

				<p align="justify">● Wireless communications amongst EV, meter, EVSE, and gateway if used is often IEEE 802.15.4 (CSMA/CA)&nbsp;</p>

				<p align="justify">○ Mesh network topologies will likely be seen in future deployments&nbsp;</p>

				<p align="justify">● WiFi or cellular can be used in the EVSE-to-gateway communication</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">WAMPAC</p>
			</td>
			<td valign="top">

				<p align="justify">● GPS signaling between PMUs and Satellites is of primary concern for WAMPAC. Manipulation of this time variable can be attempted here in this sub-category of tasks or in the next sub-category of tasks&nbsp;</p>

				<p align="justify">● Other wireless communication is not commonly used in WAMPAC due to latency requirements, however cellular and WIFI communications could be considered in the rare occasions when they are used</p>
			</td>
		</tr>
	</tbody>
</table>


![Figure 5.1a: RF Packet Analysis Task Flow](https://statics.bsafes.com/images/papers/nescor-guide-to-penetration-testing-for-electric-utilities-fig-5-1a.png)
Figure 5.1a: RF Packet Analysis Task Flow

5.1.1 RF Signal Capture 

***Level of Effort:*** Medium 

***Task Description:*** Use a tool (such as a USRP2) to capture the RF communications of the target field device. Discover of the frequencies used are usually straightforward by referencing the FCC or other regulatory license IDs printed on the outside of the transmitting device, through vendor documentation, or even patent fililings. 

***Task Goal:*** Obtain data for following tasks.

#### 5.1.2 Spread Spectrum Recovery 

***Level of Effort:*** Extremely High 

***Task Description:*** If Spread Spectrum (SS) techniques are used on the signal, knowledge of the SS algorithm must be obtained either from documentation, through recovery in the disassembled firmware, or through capture of all signal components in the used spectrum. Use of a tool such as GNU Radio to capture and discover the algorithm is possible, but very time consuming. 

***Task Goal:*** Obtain data for following tasks.

#### 5.1.3 Signal Demodulation 

***Level of Effort:*** Medium 

***Task Description:*** Use a tool such as GNU Radio to demodulate the signal. If spread spectrum technologies are used, this greatly increases the level of effort of this task. 

***Task Goal:*** Obtain data for following tasks.

##### 5.1.4 Network Traffic Extraction

***Level of Effort:*** Medium 

***Task Description:*** Use a tool to decode and extract communications payload from RF capture. 

***Task Goal:*** Obtain data for following tasks.

#### 5.1.5 RF Signal Transmission 

***Level of Effort:*** Medium to High 

***Task Description:*** Use a tool to transmit RF signals at the appropriate frequencies and hopping patterns to either replay captured data, impersonate the target field device, or attempting to cause denial of service scenarios. 

***Task Goal:*** Identify vulnerabilities in the RF signaling.

### 5.2 Network Protocol Analysis
This subcategory of penetration tasks focuses on analysis of network protocols above the PHY/MAC layer or from layer two and above in the OSI model.


<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top">

				<p align="justify">AMI</p>
			</td>
			<td valign="top">

				<p align="justify">● Meter to headend communications such as C12.21, C12.22, DLMS/COSEM, or other smart meter protocols&nbsp;</p>

				<p align="justify">● Headend to other data center servers such as the MDMS that often use SOAP or REST web services</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DR</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications between energy resources and the gateway&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Often using 6LoWPAN, Zigbee, and SEP&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Proprietary application protocols with IEEE 802.15.4 are widely used&nbsp;</p>

				<p align="justify">● Communicates between the gateway and the DRAS&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ OpenADR 1.0/2.0 protocol over web services (SOAP or REST binding)</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DER</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications between the managed generation and storage devices and the Customer Energy Management System&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Often using SEP&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Proprietary application layer protocols are also sometimes used&nbsp;</p>

				<p align="justify">● Communications between the DER Management Server and the managed generation and storage devices&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Often using SEP&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Proprietary application layer protocols are also sometimes used&nbsp;</p>

				<p align="justify">● Communications between the DER Management Server and other upstream servers that are dependent on its DER data&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Usually using REST or SOAP web services</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DGM</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications between DGM devices and their management servers&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Often using telenet, ftp, SSH, or raw TCP&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Sometimes these will use web services (such as SOAP or REST) and sometimes directly configured via a web interface on each device&nbsp;</p>

				<p align="justify">● Communications between DGM devices and DGM Server or other SCADA Historians&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Usually using Modbus, DNP3, or one of the IEC 61850 protocols</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">ET</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications amongst EV, meter, EVSE, and gateway&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Often 6LoWPAN, Zigbee, and SEP&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Protocols such as ISO/IEC 15118 and ISO/IEC 1851</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Proprietary protocols at the application layer, often over IEEE 802.15.4&nbsp;</p>

				<p align="justify">● Communications between Gateway and EV management server&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Often over web services (SOAP or REST binding)&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Simple HTTP connections (GET and PUT)&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Binary connections (over TCP or UDP)</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">WAMPAC</p>
			</td>
			<td valign="top">

				<p align="justify">● Communications often leveraging one of the versions of C37.118 or IEC-61850-90-5&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Communication between PMU and PDC&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Communication between PDC and other PDCs&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ PDC to phasor gateway&nbsp;</p>

				<p align="justify">● Phasor application to PDC and phasor application to phasor application often using SOAP or REST web services.&nbsp;</p>

				<p align="justify">● Manipulation of timestamps in PDU and PDC traffic should be included to determine how this affects WAMPAC applications</p>
			</td>
		</tr>
	</tbody>
</table>


![Figure 5.2a: Network Protocol Analysis Task Flow](https://statics.bsafes.com/images/papers/nescor-guide-to-penetration-testing-for-electric-utilities-fig-5-2a.png)
Figure 5.2a: Network Protocol Analysis Task Flow

#### 5.2.1 Network Protocol Traffic Capture 

***Level of Effort:*** Low 

***Task Description:*** Use a tool to capture sample communications. Attempt to cause known actions that result in communications between devices, such as firmware updates, and capture this communication individually to facilitate later analysis. Obtain samples of all target functionality. 

***Task Goal:*** Obtain data for the following tasks.

#### 5.2.2 Network Protocol Cryptographic Analysis 

***Level of Effort:*** Medium 

***Task Description:*** If the traffic capture uses a known protocol, identify the negotiated cryptographic algorithm and key length to determine if any known vulnerabilities exist. If traffic capture is using an unknown protocol and is not readable, extract payloads from the captured network traffic and perform an entropy analysis to determine if the data is encrypted. High levels of entropy among the payload bytes often signify that encryption is being used, and weaknesses in cryptographic implementations can often be determined by variations in that entropy. 

***Task Goal:*** Determine if cryptography is being used and identify any vulnerabilities.

#### 5.2.3 Unknown Protocol Decoding 

***Level of Effort:*** High to Extremely High 
***Task Description:*** If traffic capture is using an unknown protocol, reverse engineer the network captures in an attempt to understand the protocol. Analyze each capture in light of the actions performed to initiate that traffic. For instance, if analyzing a traffic capture of a firmware update, try to identify the firmware being sent in the payload. Additionally, analyze actions such as initial registration between devices to determine if an authentication mechanism is being used. 

***Task Goal:*** Identify the purpose of blocks of data that could be used in later analysis.

#### 5.2.4 Network Protocol Fuzzing 

***Level of Effort:*** Medium to High

***Task Description:*** Use a tool to send both valid and invalid communications to both end points of the communications link individually, analyzing the results and identifying anomalies. This task includes items such as password guessing, invalid input testing, data enumeration, replaying data, susceptibility to Man-in-the-Middle (MitM) attacks, etc. 

***Task Goal:*** Identify vulnerabilities in the network protocol implementation.

#### 5.2.5 Network Protocol Exploitation 

***Level of Effort:*** High to Extremely High 

***Task Description:*** Based on the findings from previous tasks, determine feasible attacks which can be launched on the field technician interface. For example, if devices are not required to authenticate themselves when joining a field area network, it may be possible to insert a ‘rogue’ node in the network or to harvest controlled devices away from their management server such as AMI headends or synchrophasor managers. Another example might be spoofing a firmware update or disconnect signal or perform an active MitM attack.

***Task Goal:*** Create proof of concept attacks to demonstrate the feasibility and business risk created by the discovered vulnerabilities.

***
#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-1/">1 Introduction</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-2/">2 Penetration Test Scoping</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-3/">3 Target System Setup</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-4/">4 Embedded Device Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-5/">5 Network Communications Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-6/">6 Server OS Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-7/">7 Server Application Penetration Tasks</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-8/">8 End-to-End Penetration Test Analysis</a></li><li> <a href="/docs/infrastructure/nescor-guide-to-penetration-testing-for-electric-utilities-9/">9 Result Interpretation and Reporting</a></li></ul>

***

</div>

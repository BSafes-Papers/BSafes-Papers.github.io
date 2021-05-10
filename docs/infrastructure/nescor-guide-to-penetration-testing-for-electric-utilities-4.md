---
layout: default
title: 4 Embedded Device Penetration Tasks   
parent: §  NESCOR Guide to Penetration Testing for Electric Utilities 
grand_parent: Infrastructure 
nav_order: 40 
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

## 4 Embedded Device Penetration Tasks
This section addresses the testing of field-deployed, embedded, microprocessor based devices which are reasonably exposed to physical attack. Hardware that is commonly deployed in areas where attackers could easily gain physical access such as on customer premises, pole-tops, or in substations should be tested using the tasks listed below. These tasks target electronic components inside these field deployed devices, namely those microchips that store data (EEPROM, Flash, RAM, MCU on-chip storage), buses that pass data between components (parallel buses and serial buses), and input interfaces used for administrative or debugging purposes (serial ports, parallel ports, infrared/optical ports). The following table will help map specific components that should be considered for each Smart Grid product domain.

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td rowspan="4" style="width: 16.0752%;" valign="bottom">AMI
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
			<td rowspan="4" style="width: 81.2109%;" valign="bottom">Meters
				<br>
				<br>Relays
				<br>
				<br>Aggregators
				<br>
				<br>Access &nbsp;points
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
		</tr>
		<tr>
			<td rowspan="2" style="width: 16.0752%;" valign="bottom">DR
				<br>
				<br>
				<br>
				<br>
			</td>
			<td valign="bottom">

				<p align="center">●</p>
			</td>
			<td valign="bottom">Energy &nbsp;resources
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">DCUs
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="2" style="width: 16.0752%;" valign="bottom">DER
				<br>
				<br>
				<br>
				<br>
			</td>
			<td valign="bottom">

				<p align="center">●</p>
			</td>
			<td valign="bottom">DER &nbsp;managed &nbsp;generation &nbsp;and &nbsp;storage &nbsp;devices
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Customer &nbsp;Energy &nbsp;Management &nbsp;System
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="6" style="width: 16.0752%;" valign="bottom">DGM
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
			<td valign="bottom">Automated &nbsp;Reclosures
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Remote &nbsp;Fault &nbsp;Indicators
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Capacitor &nbsp;Banks
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Automated &nbsp;Switches
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Load &nbsp;Monitor
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Substation &nbsp;Breakers
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="4" style="width: 16.0752%;" valign="bottom">ET
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
			<td valign="bottom">In-&shy;vehicle &nbsp;system &nbsp;(EV)
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Meters &nbsp;connected &nbsp;to &nbsp;the &nbsp;ET &nbsp;system
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Control &nbsp;units &nbsp;(EVSE)
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">ET &nbsp;Gateways
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="4" style="width: 16.0752%;" valign="bottom">WAMPAC
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
			<td valign="bottom">PMUs
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Devices &nbsp;which &nbsp;include &nbsp;PMU &nbsp;capabilities
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Field &nbsp;deployed &nbsp;PDCs
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Field &nbsp;deployed &nbsp;phasor &nbsp;gateways
				<br>
			</td>
		</tr>
	</tbody>
</table>


The overarching goal for embedded device testing is to identify vulnerabilities that allow attackers to expand their control of that single device to other devices with limited or no physical access to those other devices. For example, in AMI systems, a tester might successfully retrieve an AMI meter’s C12.18 master password, a password that protects the optical interface on the front of a meter, enabling the tester to directly interface with the optical port on other meters without having to disconnect or dismantle the other meters. This assumes that the master C12.18 password is used throughout the smart meter deployment, which unfortunately is often the case in AMI systems. 

Figure 4a below shows the overall process flow of the task sub-categories in this section. The figure shows the three task sub-categories may be performed in parallel. As in previous diagrams in this document, the colors represent the recommended likelihood that a utility should consider performing these task sub-categories, and the relative level of expertise required.


Figure 4a: Embedded Device Subcategory Flow

Each subcategory below includes a similar diagram depicting the process flow and recommended likelihood to perform each task.

**Suggested Tools:**
- Basic tools such as screw drivers, wire cutters, pliers, tin snips, etc.
- Electronics equipment such as power supply, digital multimeter, and oscilloscope
- Electronic prototyping supplies such as breadboard, wires, components, alligator jumpers, etc.
- Specialized tools to communicate directly with individual chips or capture serial communications such as a Bus Pirate or commercial equivalent such as Total Phase Aardvark/Beagle.
- Universal JTAG tool such as a Bus Blaster, GoodFET, or a RIFF Box
- Surface mount micro test clips
- Electric meter test socket
- Disassembler Software for the appropriate microprocessors to be tested
- Entropy Analysis Software
- Protocol Analysis Software

### 4.1 Electronic Component Analysis
This subcategory of penetration tasks focuses on the identification design weaknesses in the electronic components. Often these weaknesses show themselves in unprotected storage or transfer of sensitive information such as cryptographic keys, firmware, and any other information that an attacker can leverage to expand his attack. Primary targets for each Smart Grid product domain are:

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td rowspan="3" style="width: 14%;" valign="top">AMI
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
			<td valign="top">C12.18 &nbsp;passwords &nbsp;for &nbsp;optical &nbsp;ports
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Any &nbsp;cryptographic &nbsp;keys &nbsp;used &nbsp;in &nbsp;communications &nbsp;with &nbsp;other &nbsp;device (C12.21, &nbsp;C12.22, &nbsp;DLMS/COSEM, &nbsp;or &nbsp;other &nbsp;protocols &nbsp;the embedded &nbsp;field &nbsp;device &nbsp;uses)
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Firmware &nbsp;used &nbsp;on &nbsp;any &nbsp;meter, &nbsp;relay, &nbsp;or &nbsp;aggregator &nbsp;(usually &nbsp;one &nbsp;pe MCU &nbsp;on &nbsp;each &nbsp;device)
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="2" style="width: 14%;" valign="top">DR
				<br>
				<br>
				<br>
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="bottom">Cryptographic &nbsp;keys &nbsp;used &nbsp;in &nbsp;communications &nbsp;with:
				<br>○EMCS &nbsp;and &nbsp;DRAS
				<br>○Other &nbsp;devices &nbsp;in &nbsp;the &nbsp;HAN &nbsp;(such &nbsp;as &nbsp;SEP)
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Firmware &nbsp;on &nbsp;the &nbsp;field &nbsp;devices &nbsp;such &nbsp;as:
				<br>○Energy &nbsp;resources
				<br>○DCU
				<br>○BAS
				<br>○Gateways
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="2" style="width: 14%;" valign="top">DER
				<br>
				<br>
				<br>
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="bottom">Cryptographic &nbsp;keys &nbsp;stored &nbsp;and &nbsp;used &nbsp;on:
				<br>○DER &nbsp;Managed &nbsp;generation &nbsp;and &nbsp;storage &nbsp;devices
				<br>○Customer &nbsp;Energy &nbsp;Management &nbsp;Systems
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Firmware &nbsp;stored &nbsp;and &nbsp;transferred &nbsp;to:
				<br>○DER &nbsp;managed &nbsp;generation &nbsp;and &nbsp;storage &nbsp;devices
				<br>○Customer &nbsp;Energy &nbsp;Management &nbsp;System
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">DGM
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="middle">Cryptographic &nbsp;keys &nbsp;and &nbsp;firmware &nbsp;used &nbsp;on:
				<br>○Automated &nbsp;Reclosures
				<br>○Remote &nbsp;Fault &nbsp;Indicators
				<br>○Capacitor &nbsp;Banks
				<br>○Automated &nbsp;Switches
				<br>○Load &nbsp;Monitor
				<br>○Substation &nbsp;Breakers
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">ET
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>

				<p align="center">
					<br>
				</p>

				<p align="center">●</p>
			</td>
			<td valign="middle">Cryptographic &nbsp;keys &nbsp;used &nbsp;in &nbsp;communications &nbsp;with:
				<br>○EVMS
				<br>&nbsp; &nbsp; &nbsp;○ Other devices in the HAN (such as SEP)
				<br>&nbsp;Firmware on the field devices such as:
				<br>&nbsp; &nbsp; &nbsp; ○ EVSE and its control unit
				<br>&nbsp; &nbsp; &nbsp; ○ Gateways
				<br>&nbsp; &nbsp; &nbsp; ○ In-vehicle systems
				<br>&nbsp; &nbsp; &nbsp; ○ Meter
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">WAMPAC
				<br>
			</td>
			<td valign="top">
				<br>
				<br>
			</td>
			<td valign="middle">● C37-118 configuration files
				<br>● Device configurations
				<br>● Protocol passwords
				<br>● Any cryptographic keys used in communications with other devices (IEC 61850-90-5 or other PMU/PDC management protocols)
				<br>● Firmware used on the PMU and field deployed PDCs
				<br>
			</td>
		</tr>
	</tbody>
</table>


Figure 4.1a shows a typical task flow for analyzing electronic components.


Figure 4.1a: Electronic Component Analysis Task Flow


#### 4.1.1 Device Disassembly

***Level of Effort:*** Low
***Task Description:*** Disconnect power from the device and disassemble the device to gain access to the embedded electronic components. Attempt to do a non-destructive disassembly if possible. Document the entire process to later facilitate reassembly. Identify the existence and function of any physical tamper mechanisms protecting the device. 

***Task Goal:*** Gain physical access to embedded components and electronic buses for further testing. Identify any methods that could be used to bypass the tamper mechanisms.

#### 4.1.2 Circuit Analysis

***Level of Effort:*** Low

***Task Description:*** Document the electronic circuit by taking pictures, reading chip IDs, tracing buses, and identifying major electronic functionality.

***Task Goal:*** Gain information about the embedded hardware and identify potential electronic components for attack.

#### 4.1.3 Datasheet Analysis

***Level of Effort:*** Medium
***Task Description:*** Find, download, and analyze all pertinent datasheets and related documentation for each major electronic component inside the device, to identify possible security weaknesses and attack angles. 

***Task Goal:*** Gain information about the function of each component and how to interface directly with each component. Identify target components and buses for following tasks.

#### 4.1.4 Dumping Embedded Circuit Data at Rest

***Level of Effort:*** Medium
***Task Description:*** Using the datasheets, identify the pins necessary to perform data dumping. With the device powered off, connect your testing tools and perform the dump. If needed, be sure to disable any other component by triggering reset pins or by using other methods. Review the dumped data to determine if you were successful. Attempt multiple dumps and compare the results if you are doubtful about your success. 

***Task Goal:*** Obtain all data from unprotected storage devices for later analysis.

#### 4.1.5 Bus Snooping Embedded Circuit Data in Motion

***Level of Effort:*** Medium
***Task Description:*** Using the datasheets previously obtained, identify the pins and traces needed to perform bus snooping. With the device powered off, connect the testing tools and begin capture. Power on the device and capture sufficient data samples from each target bus. Review dumped data to identify if you were successful. Attempt multiple dumps and compare results if you are doubtful about your success. 

***Task Goal:*** Obtain data samples from all major buses for later analysis.

#### 4.1.6 String Analysis of Retrieved Data

***Level of Effort:*** Low
***Task Description:*** Use tools and multiple decoding methods to decode each obtained data. Within the logical context of the data source, identify human readable strings and other anomalies. Other identifiers may be byte patterns signifying where firmware image files begin and end. 

***Task Goal:*** Identify symmetric cryptographic keys, firmware images, and other items of interest.

#### 4.1.7 Entropy Analysis of Retrieved Data

***Level of Effort:*** Low to Medium
***Task Description:*** Analyze obtained data sets for blocks of data that portray high levels of entropy. Small data blocks with high entropy often signify asymmetric cryptographic keys and usually correspond to common key length sizes. Larger data blocks with high levels of entropy often signify encrypted data. Attempt to use suspected cryptographic keys to decrypt encrypted data blocks or encrypted communications traffic. 

***Task Goal:*** Identify asymmetric cryptographic keys and encrypted data objects.

#### 4.1.8 Systematic Key Search Through Data Sets

***Level of Effort:*** Low

***Task Description:*** Use tools to identify cryptographic keys by attempting to use possible blocks of data from each obtained data set as the cryptographic key. For instance, if the tool is trying to identify a 128 bit symmetric key, the tool will systematically attempt to use each 128 bit data block as a potential cryptographic key to decrypt a known block of encrypted data or a known capture of encrypted communications traffic. In this case, the tool will try bits 0 through 127 as a potential cryptographic key, then try bits 1 through 128, then bits 2 through 129, and so on. 

***Task Goal:*** Identify symmetric and asymmetric cryptographic keys.

#### 4.1.9 Decoding of Retrieved Data

***Level of Effort:*** High

***Task Description:*** Reverse engineering of the data in an attempt to understand its purpose. For instance, testers could attempt to understand the captured data blocks to determine what each set of bytes represent in the serial bus protocol or the data stored in the flash/EEPROM chips. This could be done by sending known commands or setting known configurations and attempting to identify in the data blocks where those commands and configurations are transmitted and stored. 

***Task Goal:*** Identify the purpose of blocks of data that could be used in exploitation attempts.

#### 4.1.10 Embedded Hardware Exploitation

***Level of Effort:*** High to Extremely High

***Task Description:*** Based on the findings from previous tasks, determine feasible attacks that can be launched on the embedded components.

***Task Goal:*** Create proof of concept attacks to demonstrate the feasibility and business risk created by the discovered vulnerabilities

### 4.2 Field Technician Interface Analysis
Most embedded devices provide physical interfaces for local configuration and debugging. The tasks in this sub-category target any serial-based management port or physical interfaces on deployed field devices. Non-serial based management interfaces such as web based interfaces accessible via network interfaces are addressed in the “Server Application Penetration Tasks” section later in this document. Primary targets for each Smart Grid product domain are:

<p>
	<br>
</p>

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
			<td valign="top">Infrared &nbsp; optical &nbsp; port &nbsp; on &nbsp; the &nbsp; front &nbsp; of &nbsp; meters &nbsp; often &nbsp; using &nbsp; th C12.18 &nbsp;protocol &nbsp;for &nbsp;communications.
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Administrative &nbsp; interfaces &nbsp; such &nbsp; as &nbsp; serial &nbsp; ports &nbsp; (RS-&shy;232) &nbsp; and other &nbsp;physical &nbsp;administrative &nbsp;interfaces &nbsp;on:
				<br>○Relays
				<br>○Aggregators
				<br>○Access &nbsp;points
				<br>○Routers
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">DR
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="middle">RS-&shy;232 &nbsp;and &nbsp;other &nbsp;serial &nbsp;interfaces, &nbsp;or &nbsp;physical &nbsp;interfaces &nbsp;on:
				<br>○Energy &nbsp;resources
				<br>○DCUs
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">DER
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="middle">Administrative &nbsp; interfaces &nbsp; such &nbsp; as &nbsp; serial &nbsp; ports &nbsp; (RS-&shy;232) &nbsp; and other &nbsp;physical &nbsp;administrative &nbsp;interfaces &nbsp;on:
				<br>○DER &nbsp;managed &nbsp;generation &nbsp;and &nbsp;storage &nbsp;devices
				<br>○Customer &nbsp;Energy &nbsp;Management &nbsp;System
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">DGM
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="middle">Administrative &nbsp;interfaces &nbsp;such &nbsp;as &nbsp;serial &nbsp;ports &nbsp;(RS-&shy;232) &nbsp;and other &nbsp;physical &nbsp;administrative &nbsp;interfaces &nbsp;on:
				<br>○Automated &nbsp;Reclosures
				<br>○Remote &nbsp;Fault &nbsp;Indicators
				<br>○Capacitor &nbsp;Banks
				<br>○Automated &nbsp;Switches
				<br>○Load &nbsp;Monitor
				<br>○Substation &nbsp;Breakers
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">ET
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="middle">RS-&shy;232 &nbsp;and &nbsp;other &nbsp;serial &nbsp;interfaces, &nbsp;or &nbsp;physical &nbsp;interfaces &nbsp;on:
				<br>○Meters
				<br>○Control &nbsp;units ○Gateways.
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">WAMPAC
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="middle">Administrative &nbsp; interfaces &nbsp; such &nbsp; as &nbsp; serial &nbsp; ports &nbsp; (RS-&shy;232) &nbsp; and other &nbsp;physical &nbsp;administrative &nbsp;interfaces &nbsp;on:
				<br>○PMUs
				<br>○Devices &nbsp;which &nbsp;include &nbsp;PMU &nbsp;capabilities
				<br>&nbsp; &nbsp; &nbsp;○ Dield deployed PDCs
				<br>&nbsp; &nbsp; &nbsp;○ Field deployed phasor gateways
				<br>
			</td>
		</tr>
	</tbody>
</table>


This subcategory of penetration tasks focuses on the analysis and identification of vulnerabilities in these interfaces. Figure 4.2a shows a typical task flow for testing field technician interfaces.

Figure 4.2a: Field Technician Device Task Flow

### 4.2.1 Interface Functional Analysis

***Level of Effort:*** Low

***Task Description:*** Obtain required software and hardware to establish an appropriate connection to the field device, be it a serial port, infrared port, or digital display. Identify the intended functionality and features of the interface. Identify any unprotected or high-risk functions that attackers may be interested in exploiting, such as firmware updates, configurations, or security table reads. 

***Task Goal:*** Gain an understanding of the interface feature set and identify functions that should be targeted for later tasks.

#### 4.2.2 Field Technician Interface Communications Capture

***Level of Effort:*** Low

***Task Description:*** Use a hardware or software tool to intercept normal communications on the interface. Capture all identified target functions from previous tasks.

***Task Goal:*** Obtain low-level capture of targeted functions.

#### 4.2.3 Field Technician Interface Capture Analysis

***Level of Effort:*** Medium

***Task Description:*** Analyze interface captures, identifying weaknesses in authentication, authorization, and integrity controls. Gain an understanding of how data is requested and commands are sent. If the protocol uses authentication, attempt to identify the passwords or keys being sent before a session is established. For example, in the case of protocols such as C12.18 for AMI meters, attempt to identify the different levels of passwords being sent before each command. 

***Task Goal:*** Identify potential vulnerabilities and attacks.

#### 4.2.4 Field Technician Interface Endpoint Impersonation

***Level of Effort:*** Low to Medium

***Task Description:*** Use an attack tool to impersonate either end of the field technician interface. For instance, this attack tool could simulate the field technician tool while communicating with the field device interface, or the attack tool could simulate the field device interface while communicating with the field device tool. 

***Task Goal:*** Obtain a usable attack point to perform later tasks

#### 4.2.5 Field Technician Interface Fuzzing 

***Level of Effort:*** Medium to High 

***Task Description:*** Use or create a fuzzing tool to send both valid and invalid communications to the target interface, analyzing the results and identifying anomalies. This task includes items such as password guessing, invalid input testing, data enumeration, etc. 

***Task Goal:*** Identify vulnerabilities in the interface implementation and obtain data not otherwise available from any field device vendor tool provided to the utility.

#### 4.2.6 Field Technician Interface Exploitation 

***Level of Effort:*** High to Extremely High 

***Task Description:*** Based on the findings from previous tasks, determine feasible attacks that can be launched on the field technician interface. Attempt to use any authentication or cryptographic keys retrieved from one meter on different meters to identify shared passwords and cryptographic keys.

***Task Goal:*** Create proof of concept attacks to demonstrate the feasibility and business risks created by the discovered vulnerabilities.

### 4.3 Firmware Binary Analysis 

This subcategory of penetration tasks focuses on the identification of vulnerabilities in binary firmware. These tasks do not describe traditional software source code review, rather they describe the techniques that attackers would use when they gain access to a firmware image in binary format and do not have access to the firmware’s original source code. Binary analysis is very time intensive and could be of limited benefit compared to an actual source code review focusing on security flaws. These tasks are primarily provided as an alternative for those utilities and organizations that do not have access to the source code of the products they are testing. It is expected that very few utilities will perform this subcategory of penetration tasks. For those parties interested in this type of analysis, consider the following firmware images in each Smart Grid product domain.

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td rowspan="5" style="width: 16.0752%;" valign="top">AMI
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
				<br>
				<br>
				<br>
			</td>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Meters
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Relays
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Aggregators
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Access &nbsp;points
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Routers
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="4" style="width: 16.0752%;" valign="bottom">DR
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
			<td valign="bottom">Energy &nbsp;resources
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">DCU
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
			<td valign="top">Gateways
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="2" style="width: 16.0752%;" valign="bottom">DER
				<br>
				<br>
				<br>
				<br>
			</td>
			<td valign="bottom">

				<p align="center">●</p>
			</td>
			<td valign="bottom">DER &nbsp;managed &nbsp;generation &nbsp;and &nbsp;storage &nbsp;devices
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Customer &nbsp;Energy &nbsp;Management &nbsp;System
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="6" style="width: 16.0752%;" valign="bottom">DGM
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
			<td valign="bottom">Automated &nbsp;Reclosures
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Remote &nbsp;Fault &nbsp;Indicators
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Capacitor &nbsp;Banks
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Automated &nbsp;Switches
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Load &nbsp;Monitor
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Substation &nbsp;Breakers
				<br>
			</td>
		</tr>
		<tr>
			<td rowspan="4" style="width: 16.0752%;" valign="bottom">ET
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
			<td valign="bottom">In-&shy;vehicle &nbsp;systems
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Meters
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">Gateways
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="center">●</p>
			</td>
			<td valign="top">EVSE &nbsp;and &nbsp;its &nbsp;Control &nbsp;units
				<br>
			</td>
		</tr>
		<tr>
			<td valign="middle">WAMPAC
				<br>
			</td>
			<td valign="middle">
				<br>
				<br>
			</td>
			<td valign="middle">● PMUs
				<br>● Devices which include PMU capabilities&nbsp;
				<br>● Field deployed PDCs&nbsp;
				<br>● Field deployed phasor gateways
				<br>
			</td>
		</tr>
	</tbody>
</table>

Figure 4.3a shows a typical task flow for analysing device firmware images in their binary format.

Figure 4.3a: Firmware Binary Analysis Task Flow

This subcategory of penetration tasks assumes the firmware was obtained in previous tasks or provided directly to the tester.

#### 4.3.1 Firmware Binary Disassembly 

***Level of Effort:*** Medium  

***Task Description:*** If firmware is successfully retrieved and the tester has sufficient time and skill, disassemble the firmware and attempt to identify vulnerabilities in the instruction calls. Warning, this task often proves very difficult as many microprocessors do not have publicly available decompilers. Consequently, one may need to be created first would could result in this becoming an “Extremely High” level of effort. 

***Task Goal:*** Obtain a human readable version of the firmware for later analysis.

#### 4.3.2 Firmware Binary Code Analysis

***Level of Effort:*** High to Extremely High   

***Task Description:*** Identify weaknesses in memory use, loop structures, cryptographic functions, interesting functions, etc. This could also include the extraction of cryptographic keys or algorithms hardcoded into the firmware.   

***Task Goal:*** Identify vulnerabilities that can be exploited.

##### 4.3.3 Firmware Binary Exploitation 

***Level of Effort:*** High to Extremely High 

***Task Description:*** Based on the findings from previous steps, determine feasible attacks which can be launched at the firmware. For instance, cryptographic materials found in the firmware could be used to access protected networks and devices, or buffer overflow like attacks could be leveraged to run arbitrary code on remote devices. 

***Task Goal:*** Create proof of concept attacks to demonstrate the feasibility and business risk created by the discovered vulnerabilities.

</div>

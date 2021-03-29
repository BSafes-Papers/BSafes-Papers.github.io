---
layout: default
title: 1. Background / Introduction
parent: § DOE/DHS/DOT Volpe Technical Meeting on Electric Vehicle and Charging Station Cybersecurity Report 
grand_parent: Electric Vehicle
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

## 1. Background/Introduction
The global electric vehicle stock surpassed one million vehicles in 2015 and grew to more than two million electric vehicles in 2016.<sup>2</sup> Growing at a similar rate, the number of EV charging stations deployed globally reached two million in 2016.<sup>3</sup> In the United States, the EV stock was nearly 600,000 vehicles and EVs made up nearly one percent of total vehicle sales in 2016.<sup>4</sup>As EV and EVSE deployment continue their growth, research and development of technologies that ensure safe and secure operating conditions of the electric vehicle fleet would be cost effective and beneficial.

### 1.1 Structure of the Report
On November 29-30 2017, the U.S. Department of Energy’s (DOE) Office of Policy (OP), in collaboration with DOE’s Vehicle Technology Office (VTO), the U.S. Department of Homeland Security’s (DHS) Science and Technology Directorate (S&T) Cyber Security Division (CSD), and the U.S. Department of Transportation’s (DOT) John A. Volpe National Transportation Systems Center (Volpe), held a technical meeting on key aspects of electric vehicle (EV) and electric vehicle supply equipment (EVSE) cybersecurity. The object of the technical meeting was not to obtain any group position or consensus. Rather, the organizers were seeking as many recommendations as possible from all individuals at the meeting.

The meeting brought together diverse stakeholders from the EV environment: vehicle manufacturers, charging station manufacturers and operators, academia, and federal and state governments. The purpose of the meeting was to explore current and future research and development in EV and EVSE cybersecurity. In their discussions at this meeting, the participants identified the takeaways and gaps contained in this report. The report also includes some background information and contextual information added for the convenience of the reader.

Section 1 gives a brief background on general vehicle cybersecurity and discusses unique electric vehicle cybersecurity concerns. Section 2 summarizes discussion and provides information on how organizations within this space can improve their cybersecurity preparedness through the structure of their organizations. Section 3 summarizes ideas expressed throughout the technical meeting on how to improve EV cybersecurity before deployment in order to increase security and save costs. Section 4 digs into the importance of establishing trust through verification, across and within systems. Section 5 discusses challenges around the supply chain of EV charging equipment and liability. Section 6 discusses how to improve sector cooperation and communication to address cybersecurity concerns early and effectively.

***
<sup>2</sup> International Energy Administration. Global EV Outlook 2017: Two Million and Counting. 2017. https://www.iea.org/publications/freepublications/publication/GlobalEVOutlook2017.pdf
{: .fs-2}
<sup>3</sup> International Energy Administration. Global EV Outlook 2017: Two Million and Counting. 2017. https://www.iea.org/publications/freepublications/publication/GlobalEVOutlook2017.pdf. 
{: .fs-2}
<sup>4</sup> International Energy Administration. Global EV Outlook 2017: Two Million and Counting. 2017. https://www.iea.org/publications/freepublications/publication/GlobalEVOutlook2017.pdf.
{: .fs-2}
***

Section 7 of the report contains gaps that were identified during the recent cybersecurity technical meeting, as well as through information gleaned from discussions with Energy Sector SMEs.

### 1.2 General Vehicle Cybersecurity Concerns Background
Today’s automobiles are complex machines that can contain many embedded electronic control units (ECUs), networks to support these units, and a host of wired and wireless external interfaces. Wired interfaces include Universal Serial Bus (USB), compact disks (CDs), and secure digital cards (SD cards). Wireless interfaces include short range and long range connectivity through Bluetooth, Wi-Fi, radio frequency (RF), near-field communications (NFC), Global System for Mobile Communications (GSM), coded-division multiple access (CDMA), and Universal Mobile Telecommunications System (UMTS).

The wireless interfaces can support a host of features, including remote tire pressure monitoring systems (TPMS), telematics, and smart key/keyless entry/ignition start. They also enable vehicle-tovehicle (V2V) and vehicle-to-infrastructure (V2I) communications (collectively referred to as V2X communications), which could improve vehicle/driving efficiency, comfort, and safety. The continuing trend in vehicle architecture is a shift towards more open systems and away from the traditional closed/proprietary system type of architecture. This increased connectivity creates a number of potential security vulnerabilities in vehicles.

Supported by grants from the U.S. National Science Foundation, collaborations between researchers at the University of California San Diego and the University of Washington in 2010 and 2011 identified vehicle cybersecurity vulnerabilities:

- **Experimental Security Analysis of a Modern Automobile (2010)<sup>5</sup> : **The analysis assumed that unauthorized parties had (at least temporary) physical access to the vehicle’s computer networks (e.g. able to plug their own hardware into a port underneath the dash). The researchers analyzed and evaluated the computers within the internal networks of a modern vehicle and described the range of security issues discovered in the process.

- **Comprehensive Experimental Analyses of Automotive Attack Surfaces (2011)<sup>6</sup> :** The major objective of this work focused on three key classes of remote attack vectors without physical contact with the vehicle: indirect physical, short-range wireless, and long-range wireless. The cybersecurity testing evaluated representative examples of each of these classes of remote attack vectors and clearly found it possible to exploit these vectors.

In 2017, the U.S. Department of Transportation’s National Highway Safety Administration (NHTSA) took a proactive safety approach to protect vehicles from malicious cyber-attacks and unauthorized access by releasing proposed guidance for improving motor vehicle cybersecurity. <sup>7</sup> To ensure a comprehensive approach to cybersecurity, NHTSA has adopted a multi-faceted research approach that leverages the U.S. National Institute of Standards and Technology Cybersecurity Framework<sup>8</sup> and encourages industry to adopt practices that improve the cybersecurity posture of vehicles.

***
<sup>5</sup> http://www.autosec.org/pubs/cars-oakland2010.pdf 
{: .fs-2}
<sup>6</sup> http://www.autosec.org/pubs/cars-usenixsec2011.pdf 
{: .fs-2}
<sup>7</sup> https://www.nhtsa.gov/technology-innovation/vehicle-cybersecurity 
{: .fs-2}
<sup>8</sup> https://www.nist.gov/cyberframework
{: .fs-2}
***

#### 1.2.1 Telematics
Telematics in the automobile industry refers to the embedded system on board a vehicle that tracks the vehicle and combines wireless telecommunications and information processing to send, receive, and store information related to vehicles. For example, telematics include original equipment installed by the manufacturer, after-market add-on systems, and/or mobile device applications and programs. In addition, telematics involve a variety of applications such as GPS tracking, engine diagnostics, vehicle monitoring and drive identification, in-vehicle recording, and instant driver feedback. As the advancement in vehicle telematics/infotainment systems and integration of numerous technologies in them rapidly grow, the security vulnerabilities in vehicles equipped with telematics/infotainment systems expand exponentially.

In a basic telematics system, vehicles gather and send data on location and vehicle status to a telematics service center that stores the data which can be accessed by the account owners of that data (see Figure 1). Telematics should be thought of and treated as a system, from the vehicle to the on-board telematics devices to the communications cloud to the data management and storage systems.


![Typical Telematics System](https://statics.bsafes.com/images/papers/doe-dhs-dot-volpe-technical-meeting-on-electric-vehicle-and-charging-stations-cybersecurity-report-fig-1.png)
Figure 1. Typical Telematics System

The signal path of the data from the telematics device is also an area of concern as it is vulnerable to man-in-the-middle attacks. Cybersecurity penetration testing of after-market telematics devices has uncovered multiple vulnerabilities such as:

- Accepted unauthenticated administrative commands via Short Message Service (SMS)

- Loaded a home-grown trojan firmware

- Unauthenticated services on the Internet

- No encryption of data in transit

Of particular interest to the government fleet community is Executive Order 13693, which states:<sup>9</sup>

*“If the agency operates a fleet of at least 20 motor vehicles, improve agency fleet and vehicle efficiency and management by … collecting and utilizing as a fleet efficiency management tool, as soon as practicable but not later than 2 years after the date of this order, agency fleet operational data through deployment of vehicle telematics at a vehicle asset level for all new passenger and light duty vehicle acquisitions and for medium duty vehicles where appropriate.”*

Since most government fleet vehicles are older models, few, if any, have original equipment manufacturer (OEM) installed telematics, after-market telematics devices must be employed to meet the Executive Order.

From the federal perspective, the telematics system is considered an information system requiring Federal Information Security Management Act (FISMA) compliance. FISMA requires compliance with NIST standards. To help government fleet managers comply with FISMA, the U.S. Department of Transportation’s Volpe Center, in cooperation with the U.S. Department of Homeland Security’s Science and Technology Cybersecurity Division, created a document entitled Cybersecurity Primer for Fleet Managers which identifies 31 security controls for telematics from Draft NIST 800-53: Security and Privacy Controls for Information Systems and Organizations<sup>10</sup>. FedRAMP program provides requirements for cloud-based IT, which is relevant for telematics as well.<sup>11</sup>

#### 1.2.2 Controller Area Network (CAN) Bus
The most common embedded network in a vehicle is the Controller Area Network (CAN) bus. All traffic to and from the components on the network is broadcasted simultaneously. Each component “listens” to all message traffic but only acts on messages explicitly addressed to it and ignores all others.

The CAN bus connects almost all of the components responsible for the operation of the vehicle and was originally designed with maintenance in mind. Maintenance personnel focused on the operations, troubleshooting, and fine-tuning of the automobile must have access to the network. This access is provided via an on-board diagnostics (OBD) port located within the cabin of the vehicle, usually under the steering wheel. Starting in 1996 in the United States, and 2001 in Europe, every vehicle is required to contain a standardized common access port to the CAN, such as OBD-II.

Anyone can control the flow of data by sending a data packet to a target electronic control unit (ECU) through the CAN bus. This method of injecting data packets can match any data packet transmitted across the network, including data packets that control functions like vehicle speed, braking, and steering. Since all CAN data packets are passed unauthenticated across the network, all messages are assumed to be legitimate messages originating from within the vehicle. With an open access port such as the OBD-II, any entity or device with access to that port can influence the vehicle systems on the network. Currently, there are many software and hardware tools that allow a user to broadcast custom CAN messages through the OBD-II port.

***
<sup>9</sup> Executive Order 13693: Planning for Federal Sustainability in the Next Decade. March 19, 2015. https://www.gpo.gov/fdsys/pkg/FR-2015-03-25/pdf/2015-07016.pdf 
{: .fs-2}
<sup>10</sup> National Institute of Standards and Technology. NIST 800-53: Security and Privacy Controls for Information Systems and Organizations. August 2017. https://csrc.nist.gov/CSRC/media//Publications/sp/800-53/rev-5/draft/documents/sp800-53r5-draft.pdf 
{: .fs-2}
<sup>11</sup> https://www.fedramp.gov/
{: .fs-2}
***

One of the greatest dangers with any kind of attack is repeatability. Once an attacker develops an attack, they can publish the attack steps on the web, or produce a “canned” version of the attack. A cursory search of the Internet will illustrate the extensive breadth of information shared and vehicle hacks performed utilizing the OBD-II port and CAN bus. This gives potential actors with less technical expertise the ability to carry out the attack.

Integrating after-market features, often used in fleet management, results in an expansion of the access points into the CAN bus. Many, if not all, of these devices allow external access directly to the vehicle’s CAN bus, and, thus, all vehicle components connected to it.

### 1.3 Cybersecurity Considerations for the Electric Vehicle
In addition to the vulnerabilities present in newer vehicle models, EVs present unique cybersecurity vulnerabilities because of their connections to other infrastructure and communication systems. When an EV refuels, it is physically and electronically connected to and exchanges information with EVSE (see Table 1.). The EVSE is an additional external interface into the internal network of the vehicle and to the electricity grid. While there are standards for the communications between the vehicle and the grid (Appendix A), further work could ensure that EVSE and EV cybersecurity is not compromised.

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td style="width: 43.3636%; background-color: rgb(44, 130, 201);" valign="top"><strong>Information</strong>&nbsp;
				<br>
			</td>
			<td style="width: 56.4546%; background-color: rgb(44, 130, 201);" valign="top"><strong>Description</strong>&nbsp;
				<br></td>
		</tr>
		<tr>
			<td style="width: 43.3636%;" valign="top"><strong>Customer/ vehicle/ charger ID</strong>&nbsp;
				<br>
			</td>
			<td style="width: 56.4546%;" valign="top">Unique identifying numbers for the user, vehicle, and charging station (may also include charging station location)&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 43.3636%;" valign="top"><strong>Control commands</strong>&nbsp;
				<br>
			</td>
			<td style="width: 56.4546%;" valign="top">Commands issued or received by the vehicle or charger&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 43.3636%;" valign="top"><strong>Software/ firmware downloads/ updates</strong>&nbsp;
				<br>
			</td>
			<td style="width: 56.4546%;" valign="top">Software downloaded or uploaded to vehicle or charger to facilitate charging process
				<br>
			</td>
		</tr>
	</tbody>
</table>

Table 1. Typical Data Elements Exchanged Between an EV and Charging Station


Compromised EVs and EVSE could be a potential public safety concern, similar to other compromised vehicles or utility distribution equipment.

Power flow between EVSE and electric vehicles need not (necessarily) flow in only one direction. Vehicle-to-grid (V2G) technology is being studied by DOE, the national labs,<sup>12</sup> and the Energy Sector as a way to improve the grid’s resiliency, reliability, and flexibility in load management. Future EVs could send electricity from their batteries back into the grid via smart chargers during peak times and also reverse the flow during off-peak hours to charge the EV. <sup>13</sup> Ensuring cybersecurity protections are in place is an important part of utilizing this potential use of EVs.

***
<sup>12</sup> https://www.anl.gov/energy-systems/group/vehicle-grid-interoperability
{: .fs-2}
<sup>13</sup> https://www.anl.gov/energy-systems/project/ev-smart-grid-interoperability-center
{: .fs-2}
***

Compromised EVs could spread malware to the EVSE they connect to. This could then be used to spread malware to other EVs connected to that network should the network architecture not be adequately segmented. The mobility of the EVs then could then be leveraged to “infect” other EVSE and, ultimately, other connected systems. Participants at the technical meeting mentioned that the EVSE could be used as a potential entry point for malware to spread to other systems, networks, and grid components.

In many cases, the EVSEs are connected to building energy management systems (BEMS), the electricity grid, telecommunications networks, and billing systems. Participants discussed at the meeting that due to these connections, EVs and EVSE could potentially be leveraged to cause electricity load management disruptions for buildings or the electric grid. For example, traditionally in the BEMS environment power draw is spread across multiple devices making the instance of rapid cycling of large power demands a rare if not impossible occurrence. The advent of large EVSE systems being integrated into the BEMS environment creates a concentrated system with a relatively large power draw. The accessibility and power draw of an EVSE system is a potential mechanism for disrupting the power of a building, or the electricity distribution service in a specific area. In addition, if the attacker installs persistent malware in the EVSE, the duration of the grid disruption can be extended even further.

Listed below are some potential cybersecurity issues which pertain to EVs:

- **Man-in-the-middle at charging station** - Attacker inserts themselves between the EV and the EVSE leading to possible tracking issues, monetary issues, and other privacy issues

- **Payment fraud** at charging station

 - The charger cycle does not last the full amount of time paid for

 - The charger is spoofed into providing free service

- **Privacy/tracking issues** with using EVSEs linked into Smart Grid

- **Intentional overcharging of batteries** via a cybersecurity attack causing possible severe damage to batteries/EV

- **Intentional discharging of batteries** taking the EV out of service/degrading range

- **Denial of service (DOS) attack at EVSEs** - Taking vehicles out of service if unable to re-charge

- **A malware infected EV** - A vehicular “Typhoid Mary” which passes its malware to other EVs via the EVSE

- **Malware infected EV** that passes onboard malware through an EVSE to the Smart Grid or onboard malware through networked EVSEs

- **Rapid cycling of heavy loads** to the grid through multiple compromised EVSEs in order to cause grid failure


There has been a body of EVSE security testing research conducted by DOE’s Idaho National Laboratory (INL):

- **2014-2015**<sup>14</sup>: INL conducted unbiased and independent EVSE testing for efficiency, reliability research, and cybersecurity posture (i.e. remote compromise, unauthorized access, firmware modifications, potential grid impact) on four (4) pre-production systems delivered by Siemens, Eaton, GE, and Delta. Listed below are some potential cybersecurity issues which pertain to EVs:

    - Software Development mistakes (i.e. implementation of “complex” code on a small embedded device leads to poor decision making)

    - Sanity checking of remote input lacking

    - Processes are executed with extensive privileges (i.e. root)

    - Memory corruption vulnerabilities (i.e. ARM, X86)

    -  Poor web application implementation SQL injection, cross-site scripting (XSS), input validation, and insecure credentials

    -  Billing and price information were manipulated

    -  Remote updating was very poorly implemented

    -  Malicious firmware lead to full compromise of all units from one vendor

- **2016-2018**<sup>15</sup>: INL conducted cybersecurity testing on two production Level 2 EVSEs and the testing results were only shared with the vendors. INL also conducted cybersecurity testing on a DC Level-2 Fast Charger (DCFC) with both a CHAdeMO and a SAE J1772-Combo cordset. Cybersecurity testing revealed the following findings:

    - A compromised Plug-In Electric Vehicle (PEV) charge module can infect the DCFC vehicle controllers and local servers and vice versa

    -  A compromised PEV is not only a potential safety concern, but it is also a grid network access concern. The biggest potential problem is for a coordinated charging event that causes widespread disruption of the grid

    - The cybersecurity testing identified some unknown issues that need to be resolved (e.g. who owns the EVSEs and network connections, are EVSEs considered part of the Utilities network perimeter, and can Utilities handle increased electrical loads)

In addition, there have been two hacker conferences discussions on EVSE hacking and vulnerabilities. In December 2017, the Chaos Communication Congress (CCC) Conference in Germany featured a talk titled “Charging Infrastructure for Electric Cars: Expansion Instead Of Security.”<sup>16</sup> The security researcher probed different components of the EVSE system and found security problems, such as:

- Insecure third-party ID tokens that allow copying personal card data and successfully charging with the copy

- Outdated versions of the OCPP protocol based on HTTP that allow setting up a man-in-themiddle attack by relaying the transaction

- Insecure EVSE USB ports that allow logs and configuration data to be copied to the drive via an empty flash drive which provide access to the login/password for the OCPP server via spoofed token numbers

In 2013, the Hack in-the-Box (HITB) conference in Malaysia, featured a talk titled “Who Can Hack a Plug: Infosec risk of Charging Electric Cars.” The security researcher identified potential EVSE vulnerabilities based on public information (e.g. vendor web sites):<sup>17</sup>

***
<sup>14</sup>https://www.energy.gov/sites/prod/files/2014/03/f13/vss096_francfort_2013_o.pdf 
{: .fs-2}
<sup>15</sup>https://avt.inl.gov/sites/default/files/pdf/presentations/VSATTOctober2015CANBusOverview.pdf 
{: .fs-2}
<sup>16</sup> https://www.v3.co.uk/v3-uk/news/3024499/kaspersky-warning-over-electric-car-charging
{: .fs-2}
<sup>17</sup> https://conference.hitb.org/hitbsecconf2013ams/materials/D2T2%20-%20Ofer%20Shezaf%20%20The%20Infosec%20Risks%20of%20Charging%20Electric%20Cars.pdf
{: .fs-2}
***

- Firmware can be extracted to identify eavesdropping points and access encryption keys

- RFID and protocol analysis to determine vulnerabilities

- Short range communications (RS-485) bandwidth and latency limits encryption and makes eavesdropping and man-in-the-middle attacks easier

- RFID short range communication is easy to eavesdrop and costly to patch

- If the same symmetric key is used for all EVSEs and payment cards does not scale and is open to relay and card attacks

- Internet of Things (IoT) protocols and web/mobile control are typically insecure

- Charge station Owners charging configuration and Driver payment methods need to be secured

#### 1.3.1 Stakeholders
There many stakeholders in the EV environment (see Table 2). Section 6 of this document addresses the importance of coordination and harmonization of research and development efforts between stakeholders.

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td style="background-color: rgb(44, 130, 201);" valign="top"><strong>Stakeholder Type </strong>
				<br>
			</td>
			<td style="background-color: rgb(44, 130, 201);" valign="top"><strong>Examples </strong>
				<br>
			</td>
			<td style="background-color: rgb(44, 130, 201);" valign="top"><strong>Links to the EV environment </strong>
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Government&nbsp;
				<br>agencies&nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">

				<ul>
					<li>Departments of Energy (DOE)&nbsp;</li>
					<li>Department of Transportation (DOT)&nbsp;</li>
					<li>Department of Homeland Security (DHS)&nbsp;</li>
					<li>State, local, and international governmental agencies &nbsp;</li>
				</ul>
			</td>
			<td valign="top">Vehicle and human safety; protection of critical infrastructure; advanced research on EV and EVSE technologies and cybersecurity&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Standards bodies&nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">

				<ul>
					<li>Institute of Electrical and Electronics Engineers (IEEE)&nbsp;</li>
					<li>National Institute of Standards and&nbsp;</li>
				</ul>Technology (NIST)&nbsp;
				<br>

				<ul>
					<li>Society of Automotive Engineers (SAE)&nbsp;</li>
					<li>International Organization of&nbsp;</li>
				</ul>Standardization (ISO)&nbsp;
				<br>

				<ul>
					<li>National Electrical Code (NEC)&nbsp;</li>
				</ul>
			</td>
			<td valign="top">Implementation of standards and best practices for safety, security, and interoperability&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">OEMs and Tier 1&nbsp;
				<br>Suppliers&nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">- Automobile manufactures&nbsp;
				<br>
			</td>
			<td valign="top">Design and build safe and reliable EVs&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Grid owners&nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">

				<ul>
					<li>Regional Transmission Organizations&nbsp;</li>
				</ul>(RTOs)/Independent System Operators (ISOs)&nbsp;
				<br>

				<ul>
					<li>Utilities&nbsp;</li>
				</ul>
			</td>
			<td valign="top">Produce and transmit electricity, load balance the grid&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Technology&nbsp;
				<br>suppliers&nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">

				<ul>
					<li>EVSE vendors and operators&nbsp;</li>
					<li>BEMS suppliers&nbsp;</li>
					<li>Information and communications technologies (ICT)&nbsp;</li>
					<li>Central Energy Management Systems&nbsp;</li>
				</ul>(CEMS)&nbsp;
				<br>

				<ul>
					<li>Payment systems&nbsp;</li>
					<li>DER Vendors&nbsp;</li>
				</ul>
			</td>
			<td valign="top">Supply the hardware and software systems that allow the&nbsp;
				<br>EV environment to operate&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Researchers &nbsp;
				<br>
			</td>
			<td valign="top">

				<ul>
					<li>Academics&nbsp;</li>
					<li>White hat hackers&nbsp;</li>
					<li>Independent researchers&nbsp;</li>
				</ul>
			</td>
			<td valign="top">Study the EV environment for possible vulnerabilities and mitigations, design the next generation EV environment &nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">EV consumers&nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">

				<ul>
					<li>General public&nbsp;</li>
					<li>Commercial fleets&nbsp;</li>
					<li>Government fleets&nbsp;</li>
				</ul>
			</td>
			<td valign="top">End users of EV environment technologies
				<br>
			</td>
		</tr>
	</tbody>
</table>
Table 2. EV and Charging Infrastructure Stakeholders


</div>

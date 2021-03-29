---
layout: default
title: 7. Gaps and Conclusions 
parent: § DOE/DHS/DOT Volpe Technical Meeting on Electric Vehicle and Charging Station Cybersecurity Report 
grand_parent: Electric Vehicle
nav_order: 70 
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

## 7. Gaps and Conclusions

### 7.1 Identified Gaps
One of the goals of the EV and EVSE Cybersecurity Technical Meeting was to identify gaps, challenges, and opportunities in cybersecurity R&D around the interdependencies between the transportation, electricity, and communications sectors. This section of the report contains gaps that were identified during the technical meeting and gleaned from discussions with subject matter experts.

#### 7.1.1 EV Charging Infrastructure Lacks Cybersecurity Best Practices
Hundreds of thousands of electric vehicle charging stations currently exist for public and residential charging. EVSEs are a key element in the EV infrastructure; however, their use in the EV environment presents several unique cybersecurity vulnerabilities. EVSEs, particularly DC fast charging stations, could be used as a potential entry point for malware to spread to other systems, networks, and grid components. Compromised EVs and EVSEs not only present potential public safety concerns similar to other compromised vehicles or utility distribution equipment, but are also potential malware vectors to other systems because of the shared connectivity and mobility of EVs. In many cases, an EVSE is connected to a BEMS, the electric grid, telecommunications networks, and back-end billing systems. Using these connections, EVs and EVSEs could be leveraged to cause electricity load management disruptions for buildings or the grid. Corrupted EVSEs could cause damage not only to the EV that is directly connected but also to other EVSEs on the same network. In addition, EVSE have physical security vulnerabilities that can allow attackers access to interior components.

With thousands of EVSEs in service, acting as not only loads but also potentially as distributed energy resources, quick notification of a compromised EVSE is important. It is currently unknown how many manufacturers provide Intrusion Detection System (IDS)<sup>26</sup> monitoring both for technical and financial intrusion events. After an event, forensic data can be used to determine the method of attack which can provide the basis for designing mitigations. It is currently unknown what post event forensic data, if any, manufactures collect for after-event analysis.

Participants stated that in today’s environment, purchasing agents who buy EVSEs do not typically specify cybersecurity protections (e.g. secure OTA firmware update capability, authentication) for their EVSE products due to lack of EVSE cybersecurity guidelines for the EVSE acquisitions. In August 2017, the European Network for Cyber Security (ENCS), Commissioned by ElaadNL developed a document titled EV Charging Systems Security Requirements which can be leveraged by the US Energy Sector. <sup>27</sup>

Also, another gap mentioned is the EV industry lacks secure software design and development methodology guidance to design and build “secure” EVSE capabilities.

***
<sup>26</sup> An Intrusion Detection System is a device or software application that monitors a network or systems for malicious activity or policy violations. 

<sup>27</sup>https://www.elaad.nl/uploads/files/Security_Requirements_Charge_Points_v1.0_april2016.pdf
***

#### 7.1.2 End-to-end EV and Charging Infrastructure Lacks a Trust Model
The connected infrastructure for electric vehicles goes beyond the electric vehicle and electric vehicle supply equipment. Connections to BEMS, smart metering systems, utility billing, and, ultimately, the grid itself are all a part of the EV environment. In this environment, electric vehicles, the charging infrastructure, and other stakeholder groups exchange information which is critical to maintaining interoperability. This information needs to be exchanged in a secure environment to ensure quality and creditability.

There is no consensus on a trusted communication standard for securing communications between the electric vehicle and the charging infrastructure. In the future it is likely that legacy equipment updates and interoperability will also be a concern.

#### 7.1.3 EV/Charging Infrastructure Lacks Cybersecurity Testing
Penetration testing is an important aspect of cybersecurity for any device in development. Today, there is a lack of formal cybersecurity penetration testing and assessment applied to the entire EV environment. Existing EV/EVSE penetration testing has been piecemeal and not necessarily thorough. This lack of formality makes it difficult to design a functional reference security architecture as there is no clear picture of the EV and charging infrastructure’s vulnerabilities.

Participants discussed a number of areas in the EV environment which could benefit from additional and more robust penetration testing between: 

- The EV and EVSE
- The EVSE and EVSE networks
- The EVSE and BEMs
- The EVSE and electric utility

Participants stressed that in today’s environment, EVSE and connected networks could be utilized to propagate malware/attacks from one node to another node, leading to potential impacts on grid operations. In addition, participants discussed the possibility that persistent malware could be utilized to increase the duration of the grid disruption. The attacker could take advantage of:

- The inadequate integrity protections for code in the protocol translation module
- The absence of cybersecurity monitoring tools to detect the malicious activity

#### 7.1.4 Wireless Chargers Lack Common Cybersecurity Guidelines
While industry works to develop new types of charging for electric buses, electric trucks, and light passenger EVs, there is no clear guidance on the unique cybersecurity requirements for wireless power transfer (WPT) charging systems specifically.

WPT charging systems utilize an electromagnetic field to transfer energy via electromagnetic induction. A typical wireless charging system consists of a fixed unit, which supplies an alternating electrical field to a fixed induction coil. On-board the vehicle, a second induction coil receives the power from the electrometric field which is converted back into electric current and used to charge the electric vehicle’s battery pack. To charge efficiently, the vehicle coil needs to be positioned over the fixed coil within a tolerance of a few inches in the X and Y directions and several inches in the Z direction. To maintain the convenience that wireless charging offers, all communication between the EV and EVSE occurs over-the-air.

WPT charging systems face the same issues as traditional wired charging systems, but because a physical wired connection is not available in a WPT charging system, unique issues need to be considered such as:

- Additional remote attack vector to the EV where a malicious actor could potentially compromise the safety, privacy, or operation of not only charging, but other vehicle functions without physically interacting with the EV. 

- Similarly, additional remote attack vector to the EVSE where a malicious actor could compromise the safety, privacy, or operation of not only charging, but other infrastructure functions without physically interacting with the EVSE. 

- The physical and cyber security mitigations used for a traditional, wired charging system need to be redesigned because the same threat model does not apply. Two-way communication between the EV and EVSE is exposed to eavesdroppers and vulnerable to denial of service, message injection, and Man-in-the-middle (MITM) over the air. It is harder to detect a remote attack due to lack of physical evidence (e.g. surveillance cameras can be avoided and equipment does not need to be damaged/modified). Critical remote software updates can be sent over the air via the two-way communication either from the EV to the EVSE or from the EVSE to the EV depending on the implementation and deployment needs. 

- Different attacker goals including influencing the positional information of the vehicle, dangerously enabling energy transfer when a vehicle isn’t present or when a human is between the vehicle and the fixed coil, and eavesdropping on vehicle charge status or payment information need to be considered.

#### 7.1.5 Security of EV Over-the-Air (OTA) Infrastructure Update Capability
EVs and EVSEs have external connectivity, such as:
- Wi-Fi technology to allow for remote power monitoring and control of the charging state of the connected vehicle
- Gateway cellular modems and cell phone applications
- Over-the-air (OTA) firmware update capability,
- Building Energy Management Systems BEMS interfaces

Today’s EV infrastructure (i.e. EVSEs, Smart Meters, Advanced Metering Infrastructure-AMI, Demand Energy Response equipment, etc.) currently has or will have OTA firmware and software update (such as remote flash capabilities) to quickly distribute software changes and security patches. 28 OTA in the context of the EV infrastructure includes distributing new software/firmware, configuration settings, and updating encryption keys. The OTA technology generally is immature and vulnerable to cyber attacks. For example, many of the major IT companies in the world, like Microsoft, Adobe, and Apache have had their OTA repositories attacked.

Participants were uncertain about how secure the update methods for EVSE are and suggested that research is needed to address potential OTA update insecurities. The following are potential vulnerabilities that participants discussed:

- Man-in-the-middle (MITM) attacks outside or inside the EVSE
- Manipulations of EVSE configuration and firmware updates via USB ports. Since this update mechanism is frequently insecure, arbitrary code could be inserted into the EVSE. By this method, an attacker for example can make charging free for all or can steal customers' card numbers to make charges at their cost
- Compromised keys used to sign updates or servers that store these keys
- For EVSEs with OTA upgrade capability for downloading software files, an attacker could make the EVSE download malicious software files
- Attackers could target the EVSE to achieve one or more of the following goals:
     - *Read updates:* Attackers aim to learn the contents of software updates in order to reverse-engineer the EVSE firmware and/or steal intellectual property
     - *Deny functionality:* Attackers try to stop the EVSE from functioning correctly, thus causing the EVSE to fail abnormally, either temporarily or permanently
     - *Control:* Attackers try to modify the EVSE performance and functionality

- Physical access, such as an attacker manually tampering with the EVSE (e.g. ports)
- Firmware updates not digitally signed or encrypted
- Weak or no authentication (e.g. default credentials), authorization or encryption for firmware updates and use of insecure internet protocols

Insecure, legacy equipment will need to be addressed at the same time as new EV equipment is designed to have better and secure OTA capabilities.

There are secure OTA frameworks the sector could investigate or utilize. For example: 

- Internet Engineering Task Force (IETF) develops and promotes voluntary Internet standards, in particular the standards that comprise the Internet protocol suite (TCP/IP).<sup>29</sup> 

- Uptane is a compromise-resilient software update security system for the automotive industry that was funded by DHS Science and Technology (S&T) Cybersecurity Division (CSD) developed by New York University’s Tandon School of Engineering, the University of Michigan’s Transportation Research Institute, and the Southwest Research Institute.<sup>30</sup>

***
<sup>28</sup> For example, ChargePoint (https://www.chargepoint.com/products/commercial/ct4000/) and Siemens (https://www.downloads.siemens.com/downloadcenter/Download.aspx?pos=download&fct=getasset&id1=BTLV_44824) 
{: .fs-2}
<sup>29</sup> https://tools.ietf.org/html/draft-moran-suit-architecture-00 
{: .fs-2}
<sup>30</sup> https://ssl.engineering.nyu.edu/papers/kuppusamy_escar_16.pdf
{: .fs-2}
***

- NEMA Smart Grid Standards Publication SG-AMI 1-2009 - *Requirements for Smart Meter Upgradeability* (December 2016) defines functional and security requirements for the secure Smart Meter/AMI upgrade—both local and remote for industry stakeholders such as regulators, utilities, and vendors.<sup>31</sup>

- NISTIR 7823: Advanced Metering Infrastructure Smart Meter Upgradeability Test Framework (March 2015) describes conformance test requirements that may be used voluntarily by testers and/or test laboratories to determine whether Smart Meters and Upgrade Management Systems conform to the requirements of NEMA SG-AMI 1-2009. <sup>32</sup>

#### 7.1.6 Commercial EVSE Lack of Common Physical Security Guidelines
There are many differing types of EVSEs each having their own unique properties. Commercial EVSEs are public facing devices which have unique physical security challenges. Unlike personal computers and servers, which are usually kept behind locked doors, commercial charging stations are situated in public areas and are frequently left unattended and open to physical damage. Commercial EVSE equipment is often placed in public places with low to zero security. In such instances, there are windows of opportunity for potential attackers to tamper and damage the EVSE equipment physically.

Intentional physical attacks on EVSEs can occur to gain access to the EVSE’s electronics to perform a cyber-based attack, to steal components such as cabling which have a high re-sale value, or to vandalize the equipment.

In addition to intentional attacks, unintentional physical damage to EVSEs can be caused by vehicles striking the EVSE, charging cabling being cut or torn out, and miscellaneous damage to user interfaces located on the EVSE such as displays and payment systems.

Physical damage to commercial EVSEs can result in non-operational units which could have an adverse effect on consumer confidence in EVs in general. Some types of physical damage whether intentional or not, may expose the public to harmful electric current levels.

### 7.2 Conclusions and Critical Gaps
The EV and charging infrastructure cybersecurity environment is a complex mix of many sectors and stakeholders. The joint DOE/DHS/DOT-Volpe Center EV and Charging Infrastructure Cybersecurity Technical Meeting was a first of its kind to bring together these disparate entities. Through presentations, breakout sessions, and general discussions, participants were able to discuss the issues at hand, identify gaps within the industry, talk about possible solutions, and establish connections between all the different stakeholders in attendance.

As these gaps identified in Section 7.1 illustrate, there are multiple challenges to securing the EV environment. Throughout the technical meeting, participants particularly focused on two of these gaps as critical for DOE and private industry to address:

***
<sup>31</sup> https://www.nema.org/Standards/Pages/Requirements-for-Smart-Meter-Upgradeability.aspx#download 

<sup>32</sup> http://nvlpubs.nist.gov/nistpubs/ir/2015/NIST.IR.7823.pdf

***

1. The lack of security and security best practices for EVSE charging infrastructure

2. The lack of an end-to-end trust model for validating communications 

There areas are critical because they have potential implications for the entire EV environment. Addressing these critical gaps should help focus and frame coordination between the relevant stakeholders in the energy, transportation and communication sectors.

Security analysis of this large and complex problem is necessary and requires coordinated and collaborative research across the different systems impacted by EVs and EVSE. Several federal agencies and offices (including DOE, DHS, and DOT) and industry are pursuing R&D in this space, with potential for further collaboration with each other and other entities. As transportation, telecommunications, and electricity system become more interconnected and interdependent, it is necessary to take a comprehensive look at the threat space and vulnerabilities and coordinate various efforts to reduce technical and policy gaps and ensure the effectiveness of existing programs.

</div>

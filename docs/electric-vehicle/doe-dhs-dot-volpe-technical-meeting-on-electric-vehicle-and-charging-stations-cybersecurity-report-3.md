---
layout: default
title: 3. Incorporating Cybersecurity into Design 
parent: § DOE/DHS/DOT Volpe Technical Meeting on Electric Vehicle and Charging Station Cybersecurity Report 
grand_parent: Electric Vehicle
nav_order: 30 
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

## 3. Incorporating Cybersecurity into Design
Cybersecurity incorporated into the design of EVs and EV charging infrastructure equipment from the onset reduces product vulnerabilities and risk of exploitation far greater than addressing cybersecurity after a system is deployed. Having cybersecurity protections from the start may help prevent basic attacks and provide a solid foundation for improving security and mitigations within the EV environment in the future.

With each addition of a new system, whether software or hardware related, security should be considered a crucial factor in the system development. Since no platform is protected from all vulnerabilities, a way to safely and securely patch the platform is needed. Developers could also establish a vulnerability disclosure program in case vulnerabilities are discovered after production has begun on the system in order to quickly respond to vulnerabilities before they are exploited.

### 3.1 Segmentation
Separating and securing key components with in a system is an essential element of secure design. Segmentation can prevent a vulnerability from compromising the whole system, by limiting an attacker’s access to a small portion of the system. If the attacker wants to move to another part of the system they would need to find another vulnerability to exploit. The attacker will be unable to move freely throughout the network which will limit the damage caused from an exploit.

Segmentation in EVs is crucial because most of the important operational functions of the vehicle communicate through the CAN bus, which can easily be compromised or misused. ECUs are allowed to communicate freely with vehicle systems by broadcasting messages throughout the CAN bus. These messages reach every component in the vehicle that is connected to the network, even if the message is not intended for that component. The correct component responds if the message was addressed specifically to it. This allows for any compromised ECU within the network to broadcast messages to other ECUs it was not intended to interact with. An example of this behavior would be an attacker gaining access to the vehicle’s CAN bus through the infotainment system, then broadcasting a message to the vehicle’s headlamps turning on the high beams. Segmentation will prevent unrelated communications between components and systems from reaching each other, such as the infotainment system communicating with critical components in the vehicle. If a component or system needs to send information to another within the network, security checks would need to be in place to authenticate the sender, its receiver, and the message itself.

### 3.2 Chipsets
The use and integration of newer chipsets (integrated circuits that manage data flows) could improve cybersecurity within a system. Older chipsets are generally basic and only provide features to carry out the task given, excluding cybersecurity. Newer chipsets provide added resources which can include extensive cybersecurity solutions as well as cybersecurity features built in on the chipset. Sometimes, when a vulnerability is found on an older chipset, it can be mitigated by adding an additional process within the chipset; however, it can be difficult to implement additional processes due to the lack of resources on the chipset.

EVs and EVSEs contain many chipsets to communicate within themselves and with each other. One of the most important chipsets is the chipset responsible for communication between the EVSE and the EV related to charging the vehicle. It is important to protect theses communications because they can provide the charging rate, vehicle identification, and billing information. Whether it’s through a chip in the chipset or processes to authenticate and check the communication, chipsets that handle this sensitive information should have security features to keep the data safe.

### 3.3 Penetration Testing
Penetration testing is an important step when incorporating cybersecurity into a system. Penetration testing is used by the manufacturer/designer to find and exploit vulnerabilities in a system before being released to the public. If a vulnerability is discovered, it shows the developers if the mitigations put in place were effective and where improvements can be made in the system to prevent a future attack. Vulnerabilities could be corrected through a patch if the issue is software related or through a redesign if the hardware contains the vulnerability.

It is best to address cybersecurity during the design phase, when it is easier to make changes with the system. Mitigations for identified vulnerabilities can be incorporated into the system and retested with another penetration test to ensure the issue has been resolved. In order to improve cybersecurity in system design most effectively, penetration testing could be done when designing the system as well as to test systems after they have been patched or redesigned in order to maintain the strongest level of security from cyberattacks. Periodic tests should also be conducted to ensure vulnerabilities weren’t missed in previous tests.

Within the EVSE, BEMS, and electrical grid network, penetration testing can help ensure the whole system is more secured against attacks and if each system has an effective mitigation solution. The test could also demonstrate that an exploited system will not have a negative impact on other systems and cause issues that can impact public safety. The results of the test will show a level of competency in the whole system to deal with vulnerabilities and the exploits used against them.

The National Electric Sector Cybersecurity Organization Resource (NESCOR) wrote a guide for penetration testing electrical utilities which can be applicable to both electric vehicles as well as electrical vehicle supply equipment.<sup>19</sup> NESCOR’s guide breaks down penetration testing into six major segments: Penetration Testing Scope, Architecture Review, Target System Setup, Penetration Tasks, End-to-End Penetration Test Analysis, and Result Interpretation and Reporting.

***
<sup>19</sup>http://smartgrid.epri.com/doc/NESCORGuidetoPenetrationTestingforElectricUtilities-v3-Final.pdf

***

Penetration Testing Scope determines which part of the system the penetration test should focus on. Architecture Review allows the team performing the penetration test to understand the system and possible vulnerabilities in the system. Target System Setup is setting up the test environment in a nonproduction system that operates as closely to the production system as possible to provide the most accurate test and results possible. Penetration Tasks is testing of each critical component in the system and can be broken down into four categories: server OS, server application, network communication, and embedded device. End-to-End Penetration Test Analysis is a communication gap analysis throughout the system. Result Interpretation and Reporting is the documentation of vulnerabilities discovered and possible mitigation solutions inside a report for future referencing.

### 3.4 Vulnerability Assessment
The NESCOR Guide to Vulnerability Assessment for Electric Utility Operations Systems can also help provide guidance in mitigating vulnerabilities found within an EVSE or BEMS.<sup>20</sup> The use of the guide could help ensure that the network, system, and system applications are prepared to deal with attackers. The guide explains the methodology the assessors should follow and how they should analyze, interpret, and report their findings. Like penetration testing, not all possible vulnerabilities will be found, but a vulnerability assessment would help mitigate a possible attack and keep the EVSE or BEMS safe.

### 3.5 EVSE Cybersecurity Procurement Guidelines
Cybersecurity procurement guidelines specify security requirements for new EVSE systems. These guides will tell buyers what cybersecurity measures to look for in EVs, EVSEs, and other systems related to the EVSE when acquiring them for their own use.

Two guides related to cybersecurity procurement language have already been written, though they are not directly related to EVSE systems. The Department of Homeland Security wrote the *Cyber Security Procurement Language for Control Systems*<sup>21</sup> Guide and the Energy Sector Control Systems Working Group (ESCSWG) wrote the *Cybersecurity Procurement Language for Energy Delivery Systems*<sup>22</sup>. It is recommended that both documents are used to produce procurement language for cybersecurity in EVSE systems as they cover both software and hardware security.

***
<sup>20</sup> http://smartgrid.epri.com/doc/nescor%20vuln%20scan%2006-26-14.pdf 

<sup>21</sup> https://ics-cert.us-cert.gov/sites/default/files/documents/Procurement_Language_Rev4_100809_S508C.pdf
 <sup>22</sup>https://energy.gov/sites/prod/files/2014/04/f15/CybersecProcurementLanguageEnergyDeliverySystems_040714_fin.pdf
***

In August 2017, the European Network for Cyber Security (ENCS), Commissioned by ElaadNL developed a document titled EV Charging Systems Security Requirements. <sup>23</sup> In addition, an EVSE Threat Assessment for Secure EV Charging Systems (April 2016) and EV Charging Systems Security Architecture (April 2016) documents were developed. These requirements can be used as part of the security requirements when new EVSE server systems are procured or set up.

***
<sup>23</sup>https://www.elaad.nl/uploads/files/Security_Requirements_Charge_Points_v1.0_april2016.pdf
{: .fs-2}
***


</div>

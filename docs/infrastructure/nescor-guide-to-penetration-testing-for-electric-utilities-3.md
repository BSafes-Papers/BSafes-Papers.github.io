---
layout: default
title: 3 Target System Setup  
parent: §  NESCOR Guide to Penetration Testing for Electric Utilities 
grand_parent: Infrastructure 
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

## 3 Target System Setup
Penetration tests should be performed on non-production systems and devices that are installed and configured for functional operation in testing or staging environments. The closer the target systems are configured to their production counterparts, the more accurate an assessment you will receive. This includes interconnectivity to dependent systems communicating with the targeted systems, regardless if those systems are in or out of scope for the penetration test. In cases where testing and staging environments do not exist, the testing team could select non-intrusive, low-risk penetration-testing tasks that can be done on production systems. NESCOR will not give guidance on which tasks are low-risk; this can only be determined by the testing team familiar with the target system. The nature of penetration testing is a trial and error method, often with unforeseen consequences in the systems being tested. Utilities would be wise to invest in testing or staging environments if they do not currently exist. 

Specific guidance for system setups of each Smart Grid product domain follows.

### 3.1 Advanced Metering Infrastructure (AMI)
AMI systems should be setup to includes all components from the meter to the headend, and if in-scope, other data center servers communicating with the headend such as MDMS or Customer Information Systems (CIS) that may communicate with the headend system or any other AMI component. At a minimum, this document assumes functional communication from the meter to the headend, and this has been established before the penetration test begins. Furthermore, it is assumed that the testers have physical access to all devices in the test environment to perform penetration tasks. 

AMI systems have been architected in a variety of different approaches. Figure 3.1a depicts a number of the most common architectures, including intermediate devices and possible communication links between the meter and the headend. This diagram attempts to include all major architecture types commonly deployed, however this means only a portion of this diagram may pertain to a specific utility. Therefore, this common architecture should be customized and tailored for specific AMI systems depending on the deployed devices and communication protocols.

Figure 3.1a: Common AMI Architecture

Figure 3.1b: Typical AMI Dataflows

Testers should be familiar with existing communication protocols that pass among different components within AMI infrastructures. Figure 3.1b depicts generic dataflows most AMI systems use in their communications between the headend and each meter.

Each one of the generic dataflows listed in Figure 3.1b represents a system functionality that attackers may leverage in their attacks. Testers should familiarize themselves with the administrative interface to the functionalities on both the meter and the headend sides. This knowledge will greatly aid testers during actual testing and enable them to trigger certain events when needed, such as initiating a firmware update while attempting to capture the update in one of the penetration test tasks. 

Penetration testing tools play a key role in the testing process. Depending on the AMI component being testing, tools may not exist for each task. For example, at the time of writing, there were very few tools available to aid testers in the generation of common AMI communication protocols such as C12.18 (for optical communications on the meter) and C12.22 for meter-to-headend communication. If time and tester skill set permit, the tester can develop these tools as part of the testing. The level of effort for such tool development should be scoped as High (17-40 hours) or Extremely High (40+ hours).

### 3.2 Demand Response (DR)
Demand Response (DR) systems should be setup to include all components from the energy resources and the gateway to the DR server (DRAS). The gateway is usually either an EMCS (Energy Management and Control System) or a HAN (Home Area Network) gateway and runs a DR client program that communicates with the DRAS. It also communicates with various types of energy resources (load, storage, and generation) to collect energy data and to send control commands. DR systems may include other intermediate devices. A customer facility may already have had a legacy BAS (Building Automation System) that has a control over some energy resources (e.g., HVAC). A DCU (Data Collection Unit) may be installed within the customer facility where energy resources are not connected to the gateway directly. Unlike the BAS, a DCU only forwards communication messages between the gateway and the energy resources. If either the BAS or the DCU is used in DR systems, the gateway indirectly communicates with the energy resources. An operator (e.g., a manager of ISO or a utility company) accesses the DRAS to begin a DR program event. At a minimum, this document assumes functional communication from the energy resources to the DRAS. Furthermore, it is assumed that the testers have physical access to all devices in the test environment to perform penetration tasks. 

DR systems can be architected in a variety of different approaches. Figure 3.2 depicts a number of the most common architectures, including intermediate devices and possible communication links between the gateway and the DRAS. This diagram attempts to include all major architecture types commonly deployed, however this means only a portion of this diagram may pertain to a specific utility. Therefore, this common architecture should be customized and tailored for specific DR systems depending on the deployed components and communication paths.

Figure 3.2a: Common DR Architecture

### 3.3 Distributed Energy Resources (DER)
Distributed Energy Resources (DER) systems are “cyber-physical” systems that can provide energy and ancillary services to the power grid, typically through the distribution system. DER systems can be generators, storage devices, and even electric vehicles if their chargers are capable of managing the charging and discharging processes. Generally these DER systems are small (usually much less than 50 MW), but potentially there will be thousands if not millions of DER systems interconnected with the distribution system. 

DER systems should be setup to includes all components from the DER Generation and Storage devices installed on the customer premises to the DER Management Server communicating with those devices, including other intermediate devices such as the Customer Energy Management System. At a minimum, this document assumes functional communication from the DER managed resources to the DER management server. Furthermore, it is assumed that the testers have physical access to all devices in the test environment to perform penetration tasks. 

DER systems can be architected in a variety of different approaches. Figure 3.3a depicts a number of the most common architectures. This diagram includes examples of various DER managed devices commonly deployed, however this means only a portion of this diagram may pertain to a specific utility. Therefore, this common architecture should be customized and tailored for specific DER systems depending on the deployed components and communication paths.

Figure 3.3a: Typical DER Architecture

### 3.4 Distribution Grid Management (DGM)
Distribution Grid Management (DGM) systems manage a wide array of sub-systems in an electric utility’s electric grid. Devices that are often monitored and controlled are: automated reclosures, remote fault indicators, capacitor Banks, automated switches, load monitors, and substation relays. Often penetration testing is focusing on only one or two of these subsystems, so system setup before testing should take this in account. At a minimum, the controlled field device, the vendor’s management server that configures the device, and the DGM servers that monitors and controls that device should be in-scope. 

The following diagram shows a sample of various devices in a substation that can be monitored and controlled by DGM systems.

Figure 3.4a: Typical DGM Controlled Substation Network

#### 3.5 Electric Transportation (ET)
Electric Transportation (ET) systems should be setup to include all components from the Electric Vehicle (EV) and the Electric Vehicle Supply Equipment (EVSE) to the EV Management Server that communicates with the EVSEs. The EV may have an in-vehicle system that is connected to the battery through the vehicle’s Car Area Network (CAN) that exchanges data with the EVSE via a wireless channel or PLC. The EVSE in a charging station usually includes a control unit, J1772 interface, and a communication module. ET systems also include other intermediate devices. A meter measures power usage for each EVSE. A gateway collects data from the meters and the EVSEs and transmits the data to the EV Management Server. At a minimum, this document assumes functional communication from the EVSE to the EV management server. Furthermore, it is assumed that the testers have physical access to all devices in the test environment to perform penetration tasks. 

ET systems can be architected in a variety of different approaches. Figure 3.5 depicts a number of the most common architectures, including intermediate devices and possible communication links between the EVSE and the EV management server. This diagram attempts to include all major architecture types commonly deployed, however this means only a portion of this diagram may pertain to a specific utility. Therefore, this common architecture should be customized and tailored for specific ET systems depending on the deployed components and communication paths.

Figure 3.5a: Common ET Architecture

### 3.6 Wide Area Monitoring, Protection, and Control (WAMPAC)
WAMPAC systems often center around synchrophasor technology and the devices that generate, receive, and utilize this synchrophasor data. WAMPAC systems should be setup to include all components from the Phasor Measurement Unit (PMU) to the WAMPAC applications leveraging that data, including other intermediate devices such as the servers that manage the PMUs, devices that provide alignment services like Phasor Data Concentrators (PDCs), phasor gateways, phasor data stores, and other such components. At a minimum, this document assumes functional communication from the PMU, its management server, and the first layer of PDCs that receive data directly from the PMU. Furthermore, it is assumed that the testers have physical access to all devices in the test environment to perform penetration tasks. 

WAMPAC systems can be architected in a variety of different approaches. Figure 3.6a depicts a number of the most common architectures, including intermediate devices and possible communication links between the syncrophasor and its dependent applications. This diagram attempts to include all major architecture types commonly deployed, however this means only a portion of this diagram may pertain to a specific utility. Therefore, this common architecture should be customized and tailored for specific WAMPAC systems depending on the deployed components and communication paths.

Figure 3.6a: Common WAMPAC Architecture

</div>

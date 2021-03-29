---
layout: default
title: 5. Ownership and Maintenance 
parent: § DOE/DHS/DOT Volpe Technical Meeting on Electric Vehicle and Charging Station Cybersecurity Report 
grand_parent: Electric Vehicle
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

## 5. Ownership and Maintenance
In the EV environment, ownership, maintenance, customization, and repair of hardware and software can be a complex issue. For EVSEs, the multitude of ownership models for charging stations makes it difficult to know who is responsible for physical and software upkeep, especially if the installer, owner, and operator are different entities. For PEVs, repairs can require specially trained personnel due to the high voltages involved in the batteries, and some owners may want to customize the software of their vehicle.

Physical maintenance issues will be relatively easy to detect (e.g. frayed or broken cables, nonfunctioning displays). The electric current levels associated with EVSE can be harmful if not handled properly, an important consideration for technicians.

Cyber monitoring and anti-tamper hardware, such as an intrusion detection system (IDS) and video surveillance, could be used to detect abnormalities in the operation of the EVSE. When an abnormality has been detected, a software patch needs to be applied. This is often accomplished by remotely applying the patch using a secure over-the-air (OTA) download method. In the event of a catastrophic failure of an EV or EVSE, forensics for analysis requires a means to record the device’s data.

Vehicle software updates present another ownership issue. If consumers need to accept or opt into an update, software in the vehicles on the road may not be uniform, even within a certain make and model year, because of time delays in accepting the update. Another issue arises when consumers make modifications to vehicles after they have purchased them. These aftermarket changes to the vehicles may create unique vulnerabilities to those vehicles. While a customer likely voids any warranty with the car manufacturer when this is done, these modified vehicles may not respond the same way to software updates issued by a vehicles manufacturer, leaving identified vulnerabilities in cars. Finally, software issues may be much more difficult to detect, whether the issue is caused by a cyber attack or bug in the vendors update.

</div>

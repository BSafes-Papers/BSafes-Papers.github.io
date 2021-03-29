---
layout: default
title: Appendix A - Electric Vehicle Technical Standards Overview 
parent: § DOE/DHS/DOT Volpe Technical Meeting on Electric Vehicle and Charging Station Cybersecurity Report 
grand_parent: Electric Vehicle
nav_order: 80 
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

## Appendix A - Electric Vehicle Technical Standards Overview
There are many standards to be found in the EV environment such as those that apply to EVSEs e.g. type of charger (DC or AC), type of charging plug etc. However without standards (even competing ones) there would be no hope of achieving interoperability within the EV environment and the table below contains a brief overview of some of the more technical standards found in the EV environment that could be impacted by EV and charging infrastructure cybersecurity. Standards also make it easier to develop requirements that can be unambiguous.

<table cellpadding="0" cellspacing="0" style="margin-right: calc(0%); width: 100%;">
	<tbody>
		<tr>
			<td style="background-color: rgb(44, 130, 201);" valign="top"><strong>Standards Body </strong>
				<br>
			</td>
			<td style="background-color: rgb(44, 130, 201);" valign="top">Standard
				<br>
			</td>
			<td style="background-color: rgb(44, 130, 201);" valign="top"><strong>Standard Title </strong>
				<br>
			</td>
			<td style="background-color: rgb(44, 130, 201);" valign="top"><strong>Remarks </strong>
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">&nbsp;Deutsches Institut f&uuml;r Normung e.V. &nbsp;(the German Institute for Standardization)- (DIN)
				<br>
			</td>
			<td valign="top">70121:2014-12
				<br>
			</td>
			<td valign="top">Electromobility - Digital communication between a D.C. EV charging station and an electric vehicle for control of D.C. charging in the Combined
				<br>Charging System
				<br>
			</td>
			<td valign="top">(For DC charging) that has no security but it is communication only from the vehicle to the off-board inverter in the EVSE. This has options for payment and authentication but not widely used. &nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">The Charging Interface Initiative (CharIN e. V.)
				<br>
			</td>
			<td valign="top">Combined Charging
				<br>System (CCS)1.0
				<br>
			</td>
			<td valign="top">Combined Charging
				<br>System Specification
				<br>1.0
				<br>
			</td>
			<td valign="top">DIN 70121:2014-12
				<br>Harmonized with SAE
				<br>J2847/2
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">The Charging Interface Initiative (CharIN e. V.)
				<br>
			</td>
			<td valign="top">CCS 2.0
				<br>
			</td>
			<td valign="top">Combined Charging
				<br>System Specification 2.0 (Mid 2018, introduction) &nbsp;
				<br>
			</td>
			<td valign="top">Retains DIN 70121:2014-12 but adds ISO 15118 ED 1. Has security but is optional.
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">The Charging Interface Initiative (CharIN e. V.)
				<br>
			</td>
			<td valign="top">CCS 3.0 (Under
				<br>Development)
				<br>
			</td>
			<td valign="top">Combined Charging
				<br>System Specification
				<br>3.0
				<br>
			</td>
			<td valign="top">Under development to include existing SAE and ISO standards plus updating for more Wireless Power Transfer (WPT) features such as adding more control and communication for vehicles approaching the ground assembly (starting from 10-50 meters out) than currently exist. 
			
			Security will be required (not optional). 
				<br>
			</td>
		</tr>
	</tbody>
</table>

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top">Society of Automotive &nbsp;Engineers (SAE)
				<br>
			</td>
			<td valign="top">J2847/2
				<br>
			</td>
			<td valign="top">Communications between Plug-In&nbsp;
				<br>Vehicles and Off-Board&nbsp;
				<br>DC Chargers&nbsp;
				<br>
			</td>
			<td valign="top">Establishes requirements and specifications for communication between Plug-in Electric Vehicle (PEV) and the DC Off-board charger.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Society of Automotive &nbsp;Engineers (SAE)
				<br>
			</td>
			<td valign="top">J2931/7
				<br>
			</td>
			<td valign="top">Security for Plug-In&nbsp;
				<br>Electrical Vehicle&nbsp;
				<br>Communications&nbsp;
				<br>
			</td>
			<td valign="top">Establishes the security requirements for digital communication between Plug-In&nbsp;
				<br>Electric Vehicles (PEV), the Electric Vehicle Supply Equipment&nbsp;
				<br>(EVSE) and the utility,&nbsp;
				<br>ESI, Advanced&nbsp;
				<br>Metering Infrastructure&nbsp;
				<br>(AMI) and/or Home&nbsp;
				<br>Area Network (HAN).&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Society of Automotive &nbsp;Engineers (SAE)
				<br>
			</td>
			<td valign="top">J2836
				<br>
			</td>
			<td valign="top">Use Cases for&nbsp;
				<br>Communication&nbsp;
				<br>Between Plug-in&nbsp;
				<br>Vehicles and the Utility&nbsp;
				<br>Grid&nbsp;
				<br>
			</td>
			<td valign="top">Establishes use cases for communication between plug-in electric vehicles and the electric power grid, for energy transfer and other applications.
				<br>
			</td>
		</tr>
	</tbody>
</table>

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top">International Organization for &nbsp;Standardization (ISO)
				<br>
			</td>
			<td valign="top">15118
				<br>(ED 2 expected end of
				<br>2018)
				<br>
			</td>
			<td valign="top">

				<p align="justify">Road vehicles-Vehicle to grid communications&nbsp;</p>

				<p align="justify">Interface&nbsp;</p>
			</td>
			<td valign="top">Specifies the communication between Electric&nbsp;
				<br>Vehicles (EV), including&nbsp;
				<br>Battery Electric&nbsp;
				<br>Vehicles and Plug-In&nbsp;
				<br>Hybrid Electric&nbsp;
				<br>Vehicles, and the&nbsp;
				<br>Electric Vehicle Supply Equipment (EVSE).&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">IEEE&nbsp;
				<br>
			</td>
			<td valign="top">2030.5 &nbsp;
				<br>(formally SEP 2.0)&nbsp;
				<br>
			</td>
			<td valign="top">Adoption of Smart Energy Profile 2.0&nbsp;
				<br>
			</td>
			<td valign="top">Defines the mechanisms for exchanging application messages, the exact messages exchanged including error messages, and the security features used to protect the application messages. 
				<br>
			</td>
		</tr>
	</tbody>
</table>

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top">Underwriters&nbsp;
				<br>Laboratories&nbsp;
				<br>
			</td>
			<td valign="top">UL2202&nbsp;
				<br>
			</td>
			<td valign="top">Standard for Electric&nbsp;
				<br>Vehicle (EV) Charging&nbsp;
				<br>System Equipment &nbsp;
				<br>&nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">Conductive charging system equipment intended to be supplied by a branch circuit of 600 volts or less for recharging the storage batteries in over-the-road electric vehicles (EV). The equipment includes off board and on board chargers&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Underwriters&nbsp;
				<br>Laboratories&nbsp;
				<br>
			</td>
			<td valign="top">UL2231&nbsp;
				<br>&nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">Standard for Personnel&nbsp;
				<br>Protection Systems for&nbsp;
				<br>Electric Vehicle (EV)&nbsp;
				<br>Supply Circuits &nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">Requirements cover conductive charging system equipment intended to be supplied by a branch circuit of 600 volts or less for recharging the storage batteries in over-the-road electric vehicles (EV). The equipment includes off board and on board chargers&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Underwriters&nbsp;
				<br>Laboratories&nbsp;
				<br>
			</td>
			<td valign="top">UL2251&nbsp;
				<br>
			</td>
			<td valign="top">Standard for Plugs,&nbsp;
				<br>Receptacles and&nbsp;
				<br>Couplers for Electric&nbsp;
				<br>Vehicles &nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">Requirements cover EV plugs, EV receptacles, vehicle inlets, vehicle connectors, and EV breakaway couplings, rated up to 800 amperes and up to 600 volts ac or dc. These devices are intended for use with conductive electric vehicle supply equipment (EVSE), and are intended to facilitate the conductive connection from the EVSE to the vehicle. 
				<br>
			</td>
		</tr>
	</tbody>
</table>

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top">Underwriters&nbsp;
				<br>Laboratories&nbsp;
				<br>
			</td>
			<td valign="top">UL2271&nbsp;
				<br>
			</td>
			<td valign="top">Batteries for use in&nbsp;
				<br>Light Electric Vehicle&nbsp;
				<br>(LEV) Applications &nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">Requirements cover electrical energy storage assemblies (EESAs) such as battery packs and combination battery packelectrochemical capacitor assemblies and the subassembly/modules that make up these assemblies for use in light electric-powered vehicles (LEVs) as defined in this standard.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Underwriters&nbsp;
				<br>Laboratories&nbsp;
				<br>
			</td>
			<td valign="top">UL2594&nbsp;
				<br>
			</td>
			<td valign="top">Electric Vehicle Supply&nbsp;
				<br>Equipment &nbsp;
				<br>&nbsp;
				<br>
			</td>
			<td valign="top">Conductive electric vehicle (EV) supply equipment with a primary source voltage of 600 V ac or less, with a frequency of 50 or 60 Hz, and intended to provide ac power to an electric vehicle with an on-board charging unit.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Open Automated&nbsp;
				<br>Demand Response&nbsp;
				<br>(ADR) Alliance&nbsp;
				<br>
			</td>
			<td valign="top">Open ADR 2.0&nbsp;
				<br>
			</td>
			<td valign="top">Open ADR 2.0&nbsp;
				<br>
			</td>
			<td valign="top">OpenADR 2.0a and b Profile Specifications provide specific implementation related information in order to build an OpenADR enabled device or system.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">Open Charge Alliance&nbsp;
				<br>(OCA)&nbsp;
				<br>
			</td>
			<td valign="top">OSCP 1.0&nbsp;
				<br>
			</td>
			<td valign="top">Open Smart Charging&nbsp;
				<br>Protocol&nbsp;
				<br>
			</td>
			<td valign="top">Protocol between charge point management system and energy management system of the site owner or the Distribution System Operator&rsquo;s (DSO) system. &nbsp;
				<br>
			</td>
		</tr>
	</tbody>
</table>

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top">North American&nbsp;
				<br>Electric Reliability&nbsp;
				<br>Corporation (NERC)&nbsp;
				<br>
			</td>
			<td valign="top">CIP-002-51.a&nbsp;
				<br>
			</td>
			<td valign="top">Cybersecurity-Bulk&nbsp;
				<br>Electrical System&nbsp;
				<br>Categorization&nbsp;
				<br>
			</td>
			<td valign="top">Identify and categorize BES Cyber Systems and their associated BES Cyber Assets for the application of cyber security requirements commensurate with the adverse impact that loss, compromise, or misuse of those BES Cyber Systems could have on the reliable operation of the BES. Identification and categorization of BES Cyber Systems support appropriate protection against compromises that could lead to mis- operation or instability in the BES.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">North American&nbsp;
				<br>Electric Reliability&nbsp;
				<br>Corporation (NERC)&nbsp;
				<br>
			</td>
			<td valign="top">CIP-005-5&nbsp;
				<br>
			</td>
			<td valign="top">Cybersecurity-
				<br>Electronic Security&nbsp;
				<br>Perimeter(s)&nbsp;
				<br>
			</td>
			<td valign="top">Manage electronic access to BES Cyber Systems by specifying a controlled Electronic Security Perimeter in support of protecting BES Cyber Systems against compromise that could lead to misoperation or instability in the BES.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">NIST&nbsp;
				<br>
			</td>
			<td valign="top">7628&nbsp;
				<br>
			</td>
			<td valign="top">Guidelines for Smart Grid Cybersecurity&nbsp;
				<br>
			</td>
			<td valign="top">Analytical framework that organizations can use to develop effective cyber security strategies tailored to their particular combinations of Smart&nbsp;
				<br>Grid-related&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">
				<br>
				<br>
			</td>
			<td valign="top">
				<br>
				<br>
			</td>
			<td valign="top">
				<br>
				<br>
			</td>
			<td valign="top">characteristics, risks, and vulnerabilities.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">NIST&nbsp;
				<br>
			</td>
			<td valign="top">Handbook 44-Section&nbsp;
				<br>3.40 &nbsp;
				<br>
			</td>
			<td valign="top">Electric Vehicle Fueling&nbsp;
				<br>Systems (Tentative&nbsp;
				<br>Code)&nbsp;
				<br>
			</td>
			<td valign="top">Code applies to devices, accessories, and systems used for the measurement of electricity dispensed in vehicle fuel applications wherein a quantity determination or statement of measure is used wholly or partially as a basis for sale or upon which a charge for service is based.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">NIST&nbsp;
				<br>
			</td>
			<td valign="top">Handbook 44-Section&nbsp;
				<br>5.55&nbsp;
				<br>
			</td>
			<td valign="top">Timing Devices&nbsp;
				<br>
			</td>
			<td valign="top">This code applies to devices used to measure time during which services are being dispensed This code also applies to&nbsp;
				<br>Electric Vehicle Supply Equipment (EVSE) when used to assess charges for time-based services in addition to those charged for electrical energy. 
				<br>
			</td>
		</tr>
	</tbody>
	</table>

</div>

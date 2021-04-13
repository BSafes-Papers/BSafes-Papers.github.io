---
layout: default
title: § DOE/DHS/DOT Volpe Technical Meeting on Electric Vehicle and Charging Station Cybersecurity Report 
parent: Electric Vehicle
has_children: true
nav_order: 982090000 
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
This is the mobile-friendly web version of the [original article](https://rosap.ntl.bts.gov/view/dot/34991).

![DOE/DHS/DOT Volpe Technical Meeting on Electric Vehicle and Charging Station Cybersecurity Report](https://statics.bsafes.com/images/papers/doe-dhs-dot-volpe-technical-meeting-on-electric-vehicle-and-charging-stations-cybersecurity-report.png)

# DOE/DHS/DOT Volpe Technical Meeting on Electric Vehicle and Charging Station Cybersecurity Report 
{: .no_toc }
## Prepared by:
{: .no_toc }
## United States Department of Transportation Volpe Center and United States Department of Energy Office of Policy
{: .no_toc }

### Final Report—March 2018
{: .no_toc } 
#### DOT-VNTSC-DOE-18-01
{: .no_toc }

Prepared for:
U.S. Department of Energy. 
1000 Independence Ave., S.W. 
Washington, DC 20585-1615

## U.S. Department of Transportation, Volpe Center
{: .no_toc }

1. TOC
{:toc}

## Disclaimer
This report was prepared as an account of work sponsored by an agency of the United States Government. Neither the United States Government nor any agency thereof, nor any of their employees, makes any warranty, express or implied, or assumes any legal liability or responsibility for the accuracy, completeness, or usefulness of any information, apparatus, product, or process disclosed, or represents that its use would not infringe privately owned rights. Reference herein to any specific commercial product, process, or service by trade name, trademark, manufacturer, or otherwise, does not necessarily constitute or imply its endorsement, recommendation, or favoring by the United States Government or any agency thereof. The views and opinions of authors expressed herein do not necessarily state or reflect those of the United States Government or any agency thereof.

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td colspan="4" valign="top"><strong>REPORT DOCUMENTATION PAGE </strong>
				<br>
			</td>
			<td colspan="3" valign="top">

				<p align="center"><em>Form Approved OMB No. 0704-0188</em>&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="7" valign="bottom">Public reporting burden for this collection of information is estimated to average 1 hour per response, including the time for reviewing instructions, searching existing data sources, gathering and maintaining the data needed, and completing and reviewing the collection of information. &nbsp;Send comments regarding this burden estimate or any other aspect of this collection of information, including suggestions for reducing this burden, to Washington Headquarters Services, Directorate for Information Operations and Reports, 1215 Jefferson Davis Highway, Suite 1204, Arlington, VA 22202-4302, and to the Office of Management and Budget, Paperwork Reduction Project (0704-0188), Washington, DC 20503.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td colspan="2" valign="top">1. AGENCY USE ONLY (Leave blank)&nbsp;
				<br>
			</td>
			<td colspan="2" valign="top">2. REPORT DATE:
				<br>March &nbsp;2018&nbsp;
				<br>
			</td>
			<td colspan="3" valign="top">3. REPORT TYPE AND DATES COVERED&nbsp;
				<br>Technical Meeting Report&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td colspan="5" valign="bottom">4. TITLE AND SUBTITLE&nbsp;
				<br>DOE/DHS/DOT Volpe Technical Meeting on Electric Vehicle and Charging Station Cybersecurity
				<br>Report
				<br>
			</td>
			<td colspan="2" valign="top">5a. FUNDING NUMBERS VXU6A1/RE572&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td colspan="5" valign="top">6. AUTHOR(S)&nbsp;
				<br>Kevin Harnett, Brendan Harris, Daniel Chin, Graham Watson
				<br>
			</td>
			<td colspan="2" valign="middle">5b. CONTRACT NUMBER&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td colspan="5" valign="bottom">

				<p align="justify">7. PERFORMING ORGANIZATION NAME(S) AND ADDRESS(ES) U.S. Department of Transportation&nbsp;</p>

				<p align="justify">John A. Volpe National Transportation Systems Center 55 Broadway</p>

				<p align="justify">Cambridge, MA 02142-1093</p>
			</td>
			<td colspan="2" valign="top">

				<p align="justify">8. PERFORMING ORGANIZATION REPORT NUMBER DOT-VNTSC-DOE-18-01 &nbsp;</p>
			</td>
		</tr>
		<tr>
			<td colspan="5" valign="top">

				<p align="justify">9. SPONSORING/MONITORING AGENCY NAME(S) AND ADDRESS(ES) U.S. Department of Energy 1000 Independence Ave., S.W.</p>

				<p align="justify">Washington, DC 20585-1615</p>
			</td>
			<td colspan="2" valign="top">10. SPONSORING/MONITORING &nbsp;AGENCY REPORT NUMBER&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td colspan="7" valign="middle">11. SUPPLEMENTARY NOTES
				<br>
			</td>
		</tr>
		<tr>
			<td colspan="7" valign="bottom">12a. DISTRIBUTION/AVAILABILITY STATEMENT 12b. DISTRIBUTION CODE&nbsp;
				<br>This document is available to the public on the National Transportation Library (NTL) <a href="http://links.govdelivery.com/track?type=click&enid=ZWFzPTEmbXNpZD0mYXVpZD0mbWFpbGluZ2lkPTIwMTgwMTAyLjgzMDgxMDUxJm1lc3NhZ2VpZD1NREItUFJELUJVTC0yMDE4MDEwMi44MzA4MTA1MSZkYXRhYmFzZWlkPTEwMDEmc2VyaWFsPTE2OTc1MDcwJmVtYWlsaWQ9a2V2aW4uaGFybmV0dEBkb3QuZ292JnVzZXJpZD1rZXZpbi5oYXJuZXR0QGRvdC5nb3YmdGFyZ2V0aWQ9JmZsPSZleHRyYT1NdWx0aXZhcmlhdGVJZD0mJiY=&&&100&&&https://rosap.ntl.bts.gov/">Repository and Open Science Access Portal (</a>ROSA P) website at: &nbsp;https://rosap.ntl.bts.gov/view/dot/34991
				<br>
			</td>
		</tr>
		<tr>
			<td colspan="7" valign="middle">13. ABSTRACT (Maximum 200 words)&nbsp;
				<br>On November 29-30, 2017, the U.S. Department of Energy&rsquo;s (DOE) Office of Policy (OP), in collaboration with DOE&rsquo;s Vehicle Technology Office (VTO), the U.S. Department of Homeland Security&rsquo;s (DHS) Science and Technology Directorate (S&amp;T) Cyber Security Division (CSD), and the U.S. Department of Transportation&rsquo;s (DOT) John A. Volpe National Transportation Systems Center (Volpe), held a technical meeting on key aspects of electric vehicle (EV) and electric vehicle supply equipment (EVSE) cybersecurity. This report summarizes key takeaways and discussion points.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td colspan="6" rowspan="2" valign="top">14. SUBJECT TERMS&nbsp;
				<br>Electric Vehicle (EV), Electric Vehicle Supply Equipment (EVSE), Cybersecurity, Charging Station, Smart Grid,&nbsp;
				<br>Utility, Building Energy Management Systems (BEMS), Vehicle Technology Office (VTO)&nbsp;
				<br>
			</td>
			<td valign="top">15. NUMBER OF PAGES
				<br>28&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">16. PRICE CODE
				<br>
			</td>
		</tr>
		<tr>
			<td valign="top">17. SECURITY CLASSIFICATION&nbsp;
				<br>&nbsp;OF REPORT&nbsp;
				<br>UNCLASS&nbsp;
				<br>
			</td>
			<td colspan="2" valign="top">18. SECURITY CLASSIFICATION&nbsp;
				<br>&nbsp;OF THIS PAGE&nbsp;
				<br>UNCLASS&nbsp;
				<br>
			</td>
			<td colspan="3" valign="top">19. SECURITY CLASSIFICATION&nbsp;
				<br>&nbsp;OF ABSTRACT&nbsp;
				<br>UNCLASS&nbsp;
				<br>
			</td>
			<td valign="middle">20. LIMITATION OF ABSTRACT
				<br>Unlimited 
				<br>
			</td>
		</tr>
	</tbody>
</table>


## Acknowledgments
The Department of Energy (DOE) and U.S. DOT Volpe Center would like to thank subject matter experts (SMEs) from the California Public Utilities Commission’s (CPUC) Vehicle-Grid Integration Communications Protocol Working Group, Idaho National Laboratory (INL), Lear Corporation, Fiat Chrysler Automotive (FCA), and Daimler AG for their insight on topics in this report. In addition, we would like to acknowledge and give thanks to all the organizations who participated in the DOE/DHS/DOT Volpe Center Technical Meeting on Electric Vehicle and Charging Station Cybersecurity on November 29-30, 2017, in Arlington, VA, and for providing their insights and expertise.

## Contents
- List of Figures

- List of Tables

- List of Abbreviations

- Executive Summary

- Background/Introduction

    - 1.1 Structure of the Report

    - 1.2 General Vehicle Cybersecurity Concerns Background

        - 1.2.1 Telematics

        - 1.2.2 Controller Area Network (CAN) Bus

    - 1.3 Cybersecurity Considerations for the Electric Vehicle

        - 1.3.1 Stakeholders

- 2 Organizational Structure

- 3 Incorporating Cybersecurity into Design

    - 3.1 Segmentation

    - 3.2 Chipsets

    - 3.3 Penetration Testing

    - 3.4 Vulnerability Assessment

    - 3.5 EVSE Cybersecurity Procurement Guidelines

- 4 Trust

- 5 Ownership and Maintenance

- 6 Coordination

    - 6.1 Standards Coordination

    - 6.2 Public Sector Coordination 

    - 6.3 Private Sector Coordination

    - 6.4 Public-Private Coordination

- 7 Gaps and Conclusions

    - 7.1 Identified Gaps

        - 7.1.1 EV Charging Infrastructure Lacks Cybersecurity Best Practices

        - 7.1.2 End-to-end EV and Charging Infrastructure Lacks a Trust Model

        - 7.1.3 EV/Charging Infrastructure Lacks Cybersecurity Testing

        - 7.1.4 Wireless Chargers Lack Common Cybersecurity Guidelines

        - 7.1.5 Security of EV Over-the-Air (OTA) Infrastructure Update Capability

        - 7.1.6 Commercial EVSE Lack of Common Physical Security Guidelines

    - 7.2 Conclusions and Critical Gaps

- Appendix A - Electric Vehicle Technical Standards Overview

## List of Figures
- Figure 1. Typical Telematics System

## List of Tables
- Table 1. Typical Data Elements Exchanged Between an EV and Charging Station

- Table 2. EV and Charging Infrastructure Stakeholders


## List of Abbreviations

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td style="background-color: rgb(44, 130, 201); width: 25.5455%;" valign="top"><strong>Abbreviation </strong>
				<br>
			</td>
			<td style="background-color: rgb(44, 130, 201); width: 74.2727%;" valign="top"><strong>Term </strong>
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">ADR&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Automated Demand Response&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">AMI&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Advanced Metering Infrastructure&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">BEMS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Building Energy Management System&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">CAN&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Controller Area Network&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">CCC&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Chaos Communications Conference&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">CCS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Combined Charging System&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">CD&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Compact Disk&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">CDMA&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Code Division Multiple Access&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">CEMS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Central Energy Management Systems&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">CharlN e.V.&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">The Charging Interface Initiative&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">DC&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Direct Current&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">DCFC&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">DC Fast Charger&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">DHS S&amp;T CSD&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Department of Homeland Security Science and Technology Cybersecurity Division&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">DIN&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Deutsches Institut f&uuml;r Normung e.V. &nbsp;(the German Institute for Standardization)&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">DOE&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Department of Energy&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">DOS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Denial of Service&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">DOT&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Department of Transportation&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">DSO&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Distribution System Operator&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">ECU&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Electronic Control Unit&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">EESA&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Electrical Energy Storage Assemblies&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">ENCS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">European Network for Cyber Security&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">ESCC&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Electricity Subsector Coordinating Council&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">ESCSWG&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Energy Sector Control Systems Working Group&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">EV&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Electric Vehicle&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">EVSE&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Electric Vehicle Supply Equipment&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">FISMA&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Federal Information Security Management Act&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">GPS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Global Positioning System&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">GSM&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Global System for Mobile Communications&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">HAN&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Home Area Network&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">HITB&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Hack-in-the-Box&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">ICT&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Information and Communications Technologies&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">IDS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Intrusion Detection System&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">IEEE&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Institute of Electrical and Electronics Engineers&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">IETF&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Internet Engineering Task Force&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">INL&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Idaho National Laboratory&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">IoT&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Internet of Things&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">ISO&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">International Organization of Standardization&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">ISO&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Independent System Operator&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="background-color: rgb(44, 130, 201); width: 25.5455%;" valign="top"><strong>Abbreviation </strong>
				<br>
			</td>
			<td style="background-color: rgb(44, 130, 201); width: 74.2727%;" valign="top"><strong>Term </strong>
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">LEV&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Light Electric Vehicle&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">MITM&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Man In The Middle&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">NEC&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">National Electrical Code&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">NERC&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">North American Electric Reliability Corporation&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">NESCOR&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">National Electric Sector Cybersecurity Organization Resource&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">NFC&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Near Field Communications
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">NHTSA&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">National Highway Traffic Safety Administration&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">NIST&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">National Institute of Standards and Technology&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">NSTC&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">National Science and Technology Council&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">OBD&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">On-Board Diagnostic&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">OCA&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Open Charge Alliance&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">OEM&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Original Equipment Manufacturer&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">OP&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Office of Policy&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">OTA&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Over The Air&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">PEV&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Plug-In Electric Vehicle&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">PHEV&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Plug-In Hybrid Electric Vehicle&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">PIN&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Personal Identification Number&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">RF&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Radio Frequency&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">RTO&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Regional Transmission Organization&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">SAE &nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Society of Automotive Engineers&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">SD&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Secure Digital&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">SME&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Subject Matter Expert&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">SMS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Short Message Service&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">TLS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Transportation Layer Security&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">TPMS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Tire Pressure Monitoring System&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">UMTS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Universal Mobile Telecommunications System&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">USB&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Universal Serial Bus&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">V2G&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Vehicle to Grid&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">V2I&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Vehicle to Infrastructure&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">V2V&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Vehicle to Vehicle&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">VTO&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Vehicle Technology Office&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">W3C&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">World Wide Web Consortium&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">WPT&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Wireless Power Transfer&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 25.5455%;" valign="top">XSS&nbsp;
				<br>
			</td>
			<td style="width: 74.2727%;" valign="top">Cross-site scripting
				<br>
			</td>
		</tr>
	</tbody>
</table>


## Executive Summary
On November 29-30, 2017, the U.S. Department of Energy’s (DOE) Office of Policy (OP), in collaboration with DOE’s Vehicle Technology Office (VTO), the U.S. Department of Homeland Security’s (DHS) Science and Technology Directorate (S&T) Cyber Security Division (CSD), and the U.S. Department of Transportation’s (U.S. DOT) John A. Volpe National Transportation Systems Center (Volpe) held a technical meeting on key aspects of electric vehicle (EV) and electric vehicle supply equipment (EVSE) cybersecurity. This report summarizes key takeaways and discussion points.

Electric vehicles are becoming a part of the transportation and mobility industry in the United States. It is during this initial development and deployment period for the EV environment that the opportunity exists to mitigate cybersecurity issues before they become widespread, ingrained, difficult, and expensive to remedy. The EV environment is a mix of multiple stakeholders, domains, hardware, and software. As the communication, electricity, and transportation systems become more integrated, cybersecurity vulnerabilities that would normally be localized, now have the ability to cause disruptions across these multiple sectors.

Modern day automobiles have cybersecurity vulnerabilities that the industry and government are working on addressing.<sup>1</sup> This report, and the preceding technical meeting, focuses on the cybersecurity vulnerabilities that are unique to electric vehicles and electric vehicle supply equipment:

- The two-way communication between the EVSE and the vehicle

- The connection between EVs, EVSE, and other systems (e.g., grid, telecommunications, buildings, etc.)

These differences could potentially lead to three main types of issues:
 - 1) Public safety hazard to the vehicle operators and/or those in the immediate vicinity

 - 2) Mobile, highly connected malware vectors

- 3) Initiating and/or exacerbating electric grid disruption

As a result of discussions during the Electric Vehicle and Charging Infrastructure Cybersecurity Technical Meeting, participants identified gaps and vulnerabilities in this threat space (see Chapter 7: Gaps and Conclusions for more detail on the gaps). The table below is a prioritized list of the gaps identified and provides a short description of each:

***
<sup>1</sup>https://www.nhtsa.gov/technology-innovation/vehicle-cybersecurity
{: .fs-2}
***

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td style="width: 33.1818%; background-color: rgb(44, 130, 201);" valign="middle">

				<p align="center"><strong>Identified Gap </strong></p>
			</td>
			<td style="width: 66.6364%; background-color: rgb(44, 130, 201);" valign="middle">

				<p align="center"><strong>Gap Description </strong></p>
			</td>
		</tr>
		<tr>
			<td style="width: 33.1818%;" valign="top"><strong>EVSE Charging Infrastructure </strong>
				<br><strong>Lacks Cybersecurity Best Practices </strong>
				<br>
			</td>
			<td style="width: 66.6364%;" valign="top">The EV industry does not have secure software design and development methodology guidance to design and build&nbsp;
				<br>&ldquo;secure&rdquo; EVSE capabilities. Purchasing agents who buy EVSEs do not typically specify cybersecurity protections (e.g. secure OTA firmware update capability, authentication) for their EVSE products due to lack of EVSE cybersecurity guidelines for the EVSE acquisitions. &nbsp;&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 33.1818%;" valign="top"><strong>End-to-End EV and Charging </strong>
				<br><strong>Infrastructure Lacks a Trust </strong>
				<br><strong>Model &nbsp;</strong>
				<br><strong>&nbsp;</strong>
				<br>
			</td>
			<td style="width: 66.6364%;" valign="top">There is no consensus on end-to-end trusted communication standards for securing communications between the electric vehicle and the charging infrastructure.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 33.1818%;" valign="top"><strong>EV/Charging Infrastructure Lacks </strong>
				<br><strong>Cybersecurity Testing &nbsp;</strong>
				<br>
			</td>
			<td style="width: 66.6364%;" valign="top">There is a lack of formal cybersecurity testing and assessment applied to the entire EV charging infrastructure.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 33.1818%;" valign="top"><strong>Wireless Chargers Lack Common </strong>
				<br><strong>Cybersecurity Guidelines &nbsp;</strong>
				<br>
			</td>
			<td style="width: 66.6364%;" valign="top">Light passenger EVs, electric buses and electric trucks have similar wireless charging communications paths, and none of them have guidance on the unique cybersecurity requirements specifically for wireless charging.&nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 33.1818%;" valign="top"><strong>EV Over-the-Air (OTA) </strong>
				<br><strong>Infrastructure Update Capability </strong>
				<br><strong>Is Immature &nbsp;</strong>
				<br><strong>&nbsp;</strong>
				<br>
			</td>
			<td style="width: 66.6364%;" valign="top">Current EV infrastructure (i.e. EVSEs, Smart Meters, Advanced Metering Infrastructure-AMI, Demand Energy Response equipment, etc). OTA update capability is immature and insecure and vulnerable to cyberattacks. Insecure legacy equipment will need to be addressed at the same time as new EV equipment is designed to have better and more secure OTA capabilities. &nbsp;
				<br>
			</td>
		</tr>
		<tr>
			<td style="width: 33.1818%;" valign="top"><strong>Commercial EVSE Lack of </strong>
				<br><strong>Common Physical Security </strong>
				<br><strong>Guidelines </strong>
				<br>
			</td>
			<td style="width: 66.6364%;" valign="top">Physical damage to commercial EVSEs can result in nonoperational units which could have an adverse effect on consumer confidence in EVs in general. &nbsp;Some types of physical damage whether intentional or not, may expose the public to harmful electric current levels. &nbsp;There is a lack of common Physical Security Guidelines for Commercial EVSE Physical Security.
				<br>
			</td>
		</tr>
	</tbody>
</table>


Throughout the technical meeting, participants particularly focused on two of these gaps as critical for government and industry to address: 

- 1.The lack of security best practices for EVSE charging infrastructure

- 2.The lack of an end-to-end trust model for validating communications

Addressing these critical gaps should help focus and frame coordination between the relevant stakeholders in the energy, transportation, and communication sectors.

</div>

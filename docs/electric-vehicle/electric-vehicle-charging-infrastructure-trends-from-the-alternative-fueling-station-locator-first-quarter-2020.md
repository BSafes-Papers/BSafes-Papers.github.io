---
layout: default
title: § Electric Vehicle Charging Infrastructure Trends from the Alternative Fueling Station Locator -  First Quarter 2020 
parent: Electric Vehicle 
nav_order: 980020000 
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
This is the mobile-friendly web version of the [original article](https://www.nrel.gov/docs/fy20osti/77508.pdf).

![Electric Vehicle Charging Infrastructure Trends from the Alternative Fueling Station Locator -  First Quarter 2020](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020.png)

# Electric Vehicle Charging Infrastructure Trends from the Alternative Fueling Station Locator: First Quarter 2020
{: .no_toc }

Abby Brown, <sup>1</sup> Stephen Lommele, <sup>1</sup> Alexis Schayowitz,<sup>2</sup> and Emily Klotz<sup>2</sup>

<sup>1</sup> National Renewable Energy Laboratory
{: .fs-2}
<sup>2</sup> ICF
{: .fs-2}

### NREL is a national laboratory of the U.S. Department of Energy Office of Energy Efficiency & Renewable Energy Operated by the Alliance for Sustainable Energy, LLC
{: .no_toc }

This report is available at no cost from the National Renewable Energy Laboratory (NREL) at www.nrel.gov/publications.

Contract No. DE-AC36-08GO28308

### Technical Report
{: .no_toc }
NREL/TP-5400-77508
Revised October 2020

### Suggested Citation
{: .no_toc }
Brown, Abby, Stephen Lommele, Alexis Schayowitz, and Emily Klotz. 2020. Electric Vehicle Charging Infrastructure Trends from the Alternative Fueling Station Locator: First Quarter 2020. Golden, CO: National Renewable Energy Laboratory. NREL/TP-5400- 77508. www.nrel.gov/docs/fy20osti/77508.pdf.

National Renewable Energy Laboratory 15013 Denver West Parkway Golden, CO 80401 303-275-3000 • www.nrel.gov

### NOTICE
{: .no_toc }
This work was authored in part by the National Renewable Energy Laboratory, operated by Alliance for Sustainable Energy, LLC, for the U.S. Department of Energy (DOE) under Contract No. DE-AC36- 08GO28308. Funding provided by U.S. Department of Energy Office of Energy Efficiency and Renewable Energy’s Vehicle Technologies Office. The views expressed herein do not necessarily represent the views of the DOE or the U.S. Government.

This report is available at no cost from the National Renewable Energy Laboratory (NREL) at www.nrel.gov/publications.

U.S. Department of Energy (DOE) reports produced after 1991 and a growing number of pre-1991 documents are available free via www.OSTI.gov.

*Cover Photo by Dennis Schroeder: NREL 48761.*

NREL prints on paper that contains recycled content.

1. TOC
{:toc}

## Errata

This report, originally published in August 2020, has been revised in October 2020 to include the analysis of an additional 2,927 public Level 2 non-networked electric vehicle supply equipment (EVSE) added to the Q4 2019 and Q1 2020 data. These stations were inadvertently excluded from the analysis in the original version published in August 2020. 

As a result, Figures 6, 7, 10, 11, 13, and 17 as well as Tables 1 and 2 were updated accordingly. In addition, the percent of stations sourced via application program interface was updated from 55% to 54%, and the percentage growth of stations in 2019 was updated from 28% to 13%. Furthermore, the text was updated to reflect that the California region came in second in both rank of EVSE per 100,000 people and in Q1 growth.

## Acknowledgments
Funding for this report came from the U.S. Department of Energy Office of Energy Efficiency and Renewable Energy’s Vehicle Technologies Office. The Station Locator team collected the data used to generate this report with the help of electric vehicle (EV) charging networks, charging infrastructure providers and developers, Clean Cities Coalition Network coordinators, industry associations, original equipment manufacturers, state and local government agencies, utilities, fleets, EV drivers, and other industry stakeholders. The authors relied on the valuable contributions of reviewers, including Eric Wood, National Renewable Energy Laboratory; Kevin Wood, Center for Sustainable Energy/San Diego Clean Cities; and Joseph Cryer, Southern California Association of Governments/Southern California Clean Cities.

## List of Acronyms
AFDC    Alternative Fuels Data Center

API       application program interface

BN       Blink network

CCS     Combined Charging System

CPN    ChargePoint network

DC      direct-current

DOE    U.S. Department of Energy

E85     ethanol blend containing 51% to 83% ethanol, depending on geography and season

EA       Electrify America network

EV       all-electric vehicle

EVC     EV Connect network

EVN    EVgo network

EVSE   electric vehicle supply equipment

EVSP   electric vehicle service provider

FCN    Francis network

FLO    FLO network

GRN  Greenlots network

kW     kilowatt

L1      Level 1 charger

L2      Level 2 charger

MUD multi-unit dwelling, also referred to as multi-family building 

NON non-networked

NREL National Renewable Energy Laboratory

OC    OpConnect network

OCPI Open Charge Point Interface

OEM  original equipment manufacturer

PEV    plug-in electric vehicle

Q1     quarter 1, or first quarter of the calendar year

SCN    SemaConnect network

TESLA Tesla Supercharger network

TESLAD  Tesla Destination network

VLTA      Volta network

WEB      Webasto network

## Executive Summary
The US. Department of Energy’s (DOE’s) Alternative Fueling Station Locator contains information on public and private non-residential alternative fueling stations in the United States and Canada and currently tracks ethanol (E85), biodiesel, compressed natural gas, electric vehicle (EV) charging, hydrogen, liquefied natural gas, and propane stations. Of these fuels, EV charging continues to experience rapidly changing technology and growing infrastructure. This report provides a snapshot of the state of EV charging infrastructure in the United States in the first calendar quarter of 2020 (Q1). Using data from the Station Locator, this report breaks down the growth of public and private charging infrastructure by charging level, network, and location. Additionally, this report measures the current state of charging infrastructure compared with the amount projected to meet charging demand for an estimated 15 million plug-in electric vehicles by 2030. This information is intended to help transportation planners, policymakers, researchers, infrastructure developers, and others understand the rapidly changing landscape for EV charging.

In Q1, all categories of electric vehicle supply equipment (EVSE) grew. Overall, there was a 6.9% increase in the number of EVSE in the Station Locator. The majority of EVSE in the Station Locator are Level 2, though both public and private direct-current (DC) fast charger EVSE grew by the largest percentage in Q1. The Northeast region saw the largest increase in public charging infrastructure in Q1, though California continues to lead the country in the number of available public EVSE.

Based on NREL’s 2017 “National Plug-In Electric Vehicle Infrastructure Analysis,” which estimated how much public and workplace Level 2 and DC fast charging infrastructure would be required in the United States to meet charging demand by 2030 (Wood 2017), about 12.0% and 49.6% of the necessary Level 2 and DC fast EVSE, respectively, have been installed as of Q1. However, 56.2% of public DC fast EVSE in the Station Locator are on the Tesla network and therefore only readily accessible to Tesla drivers.

## Table of Contents
- 1 Overview of the Station Locator

    - 1.1 EV Charging Data Sources

        - 1.1.1 Data from Charging Network APIs

        - 1.1.2 Manually Collected Data

    - 1.2 EV Charging Data Fields

- 2 Electric Vehicle Charging Infrastructure Trends

    - 2.1 Public Charging Trends

        - 2.1.1 By Charging Level

        - 2.1.2 By Network 

        - 2.1.3 By Region

        - 2.1.4 By State

- 3 Private Charging Trends

    - 3.1 By Charging Level 

    - 3.2 Workplace Charging 

    - 3.3 Multi-unit Dwelling Charging

    -3.4 Fleet Charging

- 4 Projecting Future Charging Infrastructure Needs

- 5 Developments That Could Impact Future Quarters

- 6 Conclusion

- Bibliography

## List of Figures
Figure 1. Non-Networked vs. Networked EV Charging Stations

Figure 2. Timeline of API Integrations in the Station Locator

Figure 3. EV Charging Infrastructure Hierarchy as Defined in OCPI (EVRoaming Foundation, n.d.)

Figure 4. Total Number of EVSE and EV Charging Stations in the Station Locator (2010–2020)

Figure 5. EVSE Openings in the Station Locator by Charging Level (2009–2019)

Figure 6. Q1 Growth of EVSE by Access. 

Figure 7. Q1 Growth of Public EVSE by Charging Level

Figure 8. Q1 Growth of Public DC Fast EVSE by Power Output

Figure 9. Q1 Growth of Public DC Fast Connectors by Type

Figure 10. Breakdown of Public EVSE by Network and Charging Level in Q1

Figure 11. Q1 Growth of Public EVSE by Network

Figure 12. Clean Cities Regions. 

Figure 13. Q1 Growth of Public EVSE by Clean Cities Region

Figure 14. Q1 Growth of Private EVSE by Charging Leve

Figure 15. Q1 Growth of Private Workplace EVSE by Charging Level

Figure 16. Q1 Growth of Private MUD EVSE by Charging Level

Figure 17. Current Availability and Projected Need of Public and Workplace Charging in the United States in 2030


## List of Tables
Table 1. Q1 Growth of Public EVSE by Network

Table 2. States with the Highest Rate of EVSE per 100,000 People

## 1 Overview of the Station Locator
The U.S. Department of Energy’s (DOE) Alternative Fuels Data Center (AFDC) launched in 1991 in response to the Alternative Motor Fuels Act of 1988 and the Clean Air Act Amendments of 1990 (Alternative Fuels Data Center, n.d.a.). Originally, it served as a hard copy resource for alternative fuel performance data and eventually became an internet resource in 1995. Since then, the AFDC has evolved dramatically into a robust online resource that provides a broad range of information on alternative fuels and advanced transportation technologies, including fueling and charging station data. In 2017, NREL partnered with National Resources Canada to expand the dataset to include the location of those same alternative fuel stations across Canada as the Electric Charging and Alternative Fueling Stations Locator, or Localisateur de stations de recharge et de stations de ravitaillement en carburants de remplacement (Levene et al. 2019). The Station Locator database now includes information on public and private non-residential alternative fueling stations in the United States and Canada and currently tracks ethanol (E85), biodiesel, compressed natural gas, electric vehicle (EV) charging, hydrogen, liquefied natural gas, and propane stations.

While historical data for all fuel types in the Station Locator are available, it is especially important to take an in-depth look at EV charging due to rapidly changing technology and growing infrastructure. As original equipment manufacturers (OEMs) offer more EV models, more utilities begin offering incentives for EVs and infrastructure, and states and municipalities set electrification goals, this trend is likely to continue. Using Station Locator data, this paper explores the growth of both public and private EV charging infrastructure in the United States for the first calendar quarter of 2020 (Q1).

### 1.1 EV Charging Data Sources
NREL and its data collection contractor and collaborator, ICF, use a variety of methods to gather and verify EV charging data in the Station Locator. Electric vehicle service providers (EVSPs), responsible for managing a network of EV charging stations (Fig. 1), share data directly with the Station Locator team and are the largest data source for EV charging in the Station Locator. In addition, data are collected through industry outreach, Clean Cities coordinators, and other manual methods.

![Figure 1. Non-Networked vs. Networked EV Charging Stations](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-1.png)
**Figure 1. Non-Networked vs. Networked EV Charging Stations.**

#### *1.1.1 Data from Charging Network APIs*
Prior to 2014, NREL manually collected all EV charging data, including EV charging stations managed by EVSPs. In 2014, to keep up with the rapid growth of charging infrastructure, NREL began incorporating daily updates on networked charging station data directly from EVSPs when available. NREL does this by accessing the network’s application program interface (API) and importing each network’s API data into the database. Using APIs ensures the efficiency, accuracy, and completeness of the data is maintained. As discussed in section 1.2, the Station Locator includes EV charging station open dates for manually collected data, however open dates are not available for stations provided via API. Therefore, the Station Locator team maintains a full list of open dates separately and populates open dates for stations provided via API based on the date the station appeared in the Station Locator. NREL makes this data available upon request.

Fig. 2 shows a timeline of the integration of the network APIs into the Station Locator data management process. Open Charge Point Interface (OCPI)-based APIs that have been integrated into the Station Locator are also shown in Fig. 2. See section 1.2 for more information on OCPI.

![Timeline of API Integrations in the Station Locator.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-2.png)
**Figure 2. Timeline of API Integrations in the Station Locator.**

As of March 2020, there were 28,122 public and private charging stations in the database, which are available on the Station Locator or accessible via API or data download (Alternative Fuels Data Center, n.d.b.). Of those, approximately 54% are automatically updated daily via EVSPprovided APIs while the rest are managed and updated manually.

As shown in Fig. 2, NREL completed the integration of the FLO network API in January 2020. The Station Locator team is working with additional EVSPs to access and integrate existing APIs or provide them with best practices on developing an API if they have not yet automated their data sharing. This will help ensure that station data is as current and accurate as possible, while also increasing the efficiency of the EV charging data update process.

#### *1.1.2 Manually Collected Data*
For non-networked (i.e., not connected to the internet) stations, data sources include trade media, Clean Cities coordinators, a Submit New Station form on the Station Locator website, EV charging station manufacturers, electric utilities, OEMs, state and municipal governments, private companies, and others. The Station Locator team regularly monitors news outlets for press releases on new EV charging station openings and seeks out more information as appropriate to confirm and add the EV charging data to the Station Locator.

The Station Locator team also receives semi-regular data in the form of spreadsheets from EVSPs that do not have an API available. These EVSPs include EV Connect, Tesla, and Volta. In Q1, the Station Locator team incorporated an update from all three EVSPs. The team is greatly appreciative of their continued collaboration and willingness to share regular data updates.

Finally, Clean Cities coalitions (see section 2.1.3) proactively provide information on station updates and additions throughout the year. Coalitions also serve as a valuable on-the-ground resource for stations that ICF is not able to confirm through normal station confirmation processes. Unconfirmed stations are sent to coalitions throughout the year for confirmation; if the coalition is not able to provide any additional information, the station is subsequently removed from the Station Locator.

It is important to state that notable changes in the number of EVSE in the Station Locator may be attributed to the manual data collection process. For example, as discussed in section 2.1.2, the number of EVSE on the Volta network grew significantly in Q1, which is due to the Station Locator team adding several missing Volta EVSE to the Station Locator in Q1 based on an update that Volta shared.

### 1.2 EV Charging Data Fields
Current charging infrastructure in the Station Locator generally falls into the following categories:

- **Public:** A broad category that includes EV charging located in publicly accessible areas or along highway corridors.

- **Workplace:** EV charging intended to provide charging to employees during the workday.

- **Commercial/Fleet:** EV charging intended to provide charging for electric fleet vehicles, including municipal/private fleets, car sharing, and transportation network companies.

Note that while fleet data exists in the Station Locator, stations solely for fleet use are not yet designated as such in the Station Locator. The Station Locator team has recently added this level of tracking and will therefore be able to designate stations as such moving forward. See section 3.4 for more details.

Additionally, the Station Locator does not maintain data on single-family residential charging and has minimal, yet expanding, data on charging at multi-unit dwellings (MUDs, also referred to as multi-family buildings). See section 3.3 for additional details.

In 2019, the Station Locator team began transitioning its counting logic to align with the hierarchy defined in the OCPI protocol: locations, electric vehicle supply equipment (EVSE), and connectors (EVRoaming Foundation, n.d.), as shown in Fig. 3 and described below. With this transition, the Station Locator is now counting the number of EVSE at a station location, rather than the number of connectors previously counted.

![EV Charging Infrastructure Hierarchy as Defined in OCPI (EVRoaming Foundation, n.d.).](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-3.png)
**Figure 3. EV Charging Infrastructure Hierarchy as Defined in OCPI (EVRoaming Foundation, n.d.).**

The following fuel-specific fields are tracked in the Station Locator for EV charging stations (Alternative Fuels Data Center, n.d.c.):

- EV charger information:
    - EV charging station: one or more EVSE located at the same address
    -  EVSE count: the number of outlets or ports (i.e., the number of vehicles that can simultaneously charge at a charging station)
    - Charger type
        - Level 1 (L1): 120V; 1 hour of charging = 2-5 miles of range
        - Level 2 (L2): 240V; 1 hour of charging = 10-20 miles of range
        -  Direct-current (DC) fast: 480V+; 20 minutes of charging = 60-80 miles of range
    -  Connectors (number and type)
        - NEMA: for Level 1 chargers
        - J1772: for Level 1 and Level 2 chargers
        - Combined Charging System (CCS): for DC fast chargers
        - CHAdeMO: for DC fast chargers
        - Tesla: for all charging levels for Tesla vehicles
    - Network
    - Manufacturer
    - Power output (kilowatts, kW)
- Open date
- Workplace (yes/no)
- Pricing
- On-site renewable electricity source.

We use these fields and the associated definitions for the analysis that follows.

## 2 Electric Vehicle Charging Infrastructure Trends
The purpose of this paper is to identify EV charging infrastructure trends for the first quarter of 2020. However, as previously mentioned, the Station Locator has been collecting data on alternative fueling stations since the 1990s and therefore has historical EV charging station data for several years that can serve as a baseline for more analysis.

Fig. 4 serves as a reference point for just how quickly EV charging infrastructure has grown over the last decade. The number of EVSE in the Station Locator has been growing consistently since 2011, and the number of EV charging stations also steadily increased since NREL started tracking the two figures separately in 2014. Between December 2015 and December 2019, the number of charging station records in the Station Locator nearly doubled and, in 2019 alone, the number of charging station records in the database grew by 13%.

![Figure 4. Total Number of EVSE and EV Charging Stations in the Station Locator (2010–2020).](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-4.png)
**Figure 4. Total Number of EVSE and EV Charging Stations in the Station Locator (2010–2020).<sup>1</sup>**

The breakdown of infrastructure installed by charging level has evolved in recent years, as shown in Fig. 5. Most notably, the percentage of DC fast charger EVSE installations has increased, as compared to Level 1 and Level 2 charging infrastructure.

As previously mentioned, the Station Locator does not include single-family residential charging, which contributes to the low number of Level 1 outlet installations reflected in Fig. 5.

***
<sup>1</sup> Note: Breaks in the graph represent months where data are not available, and EVSE data prior to 2019 may reflect connector numbers rather than outlet numbers.
{: .fs-2}
***

Also keep in mind that outlet opening dates are estimated based on assumptions, particularly for older stations and stations that are provided to NREL directly from charging networks through an API. In addition, for each month, note that the graph only includes stations on a charging network that were active at the time and does not include stations that had previously opened and closed.

![Figure 5. EVSE Openings in the Station Locator by Charging Level (2009–2019).](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-5.png)
**Figure 5. EVSE Openings in the Station Locator by Charging Level (2009–2019).**

As of Q1, public EVSE accounted for the majority of the EVSE in the Station Locator (Fig. 6). Public EVSE grew by 7.6%, and private EVSE grew by 3.2% (Fig. 6). Overall, the number of EVSE in the Station Locator grew by 6.9% in Q1.

![Figure 6. Q1 Growth of EVSE by Access.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-6.png)
**Figure 6. Q1 Growth of EVSE by Access.**

The following sections break down the growth of public and private EVSE further to highlight what types of EV infrastructure experienced growth in Q1 and where EV infrastructure has grown geographically. Since the number of EVSE represents the number of vehicles that can charge simultaneously at an EV charging station, the remainder of this report will focus on EVSE growth.

### 2.1 Public Charging Trends
As previously mentioned, public EV charging refers to EV charging stations that are available to all EV drivers and located in publicly accessible locations, such as commercial locations or along highway corridors. In Q1, 5,627 new public EVSE were added to the Station Locator, bringing the total number of public EVSE in the Station Locator to 79,465 and representing a 7.6% growth since the end of 2019. The following sections break down the growth of public EVSE by charging level, network, region, and state.

#### *2.1.1 By Charging Level*
As shown in Fig. 7, the majority of public EVSE in the Station Locator are Level 2, followed by DC fast and Level 1. In Q1, DC fast EVSE increased most significantly (10.6%) (Fig. 7).

![Figure 7. Q1 Growth of Public EVSE by Charging Level.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-7.png)
**Figure 7. Q1 Growth of Public EVSE by Charging Level.**

When compared with Level 1 and Level 2 chargers, DC fast chargers have the highest power output and therefore provide the most charge in the least amount of time. DC fast chargers have a standard power output of 50 kW, though DC fast chargers with higher levels of power output are available. Extreme fast charging infrastructure, which has a power output of 350 kW or more, was introduced in 2018. As shown in Fig. 8, the majority of DC fast EVSE in the Station Locator currently have the standard power output of 50 kW or less, though the growth of DC fast EVSE with power output greater than 50 kW experienced significantly more growth in Q1.

It is important to point out that of the 13,591 public DC fast EVSE in the Station Locator, power output data is currently only available for 37.1%; Fig. 8 is therefore based on power output data for a small portion of DC fast EVSE. NREL is in the process of integrating updated OCPI-based APIs to streamline the collection of power output data and create a more complete set of data. Additionally, if a DC fast EVSE has two connectors with different power outputs, only the maximum power output is counted in Fig. 8

![Figure 8. Q1 Growth of Public DC Fast EVSE by Power Output.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-8.png)
**Figure 8. Q1 Growth of Public DC Fast EVSE by Power Output.**

There are currently three types of connectors that are available for DC fast chargers: CHAdeMO, CCS, and Tesla. Of the 15,416 DC fast connectors in the Station Locator as of Q1, Tesla connectors made up the largest proportion, followed by CCS and CHAdeMO connectors (Fig. 9). CCS connectors experienced the most growth in Q1, with an 11.2% increase (Fig. 9).

![Figure 9. Q1 Growth of Public DC Fast Connectors by Type.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-9.png)
**Figure 9. Q1 Growth of Public DC Fast Connectors by Type.**

#### *2.1.2 By Network*
As discussed in section 1.1, the Station Locator team works with several EVSPs to collect EV charging infrastructure data for the Station Locator. Currently, the Station Locator includes stations on the below networks. In addition, the Station Locator collects non-networked (NON) station data, which includes stations that were previously networked.

- Blink (BN)
-  ChargePoint (CPN)
-  Electrify America (EA)
-  EV Connect (EVC)
-  EVgo (EVN)
-  FLO (FLO)
-  Francis (FCN)
-  Greenlots (GRN)
-  OpConnect (OC)
-  SemaConnect (SCN)
-  Tesla Supercharger (TESLA)
-  Tesla Destination (TESLAD)
-  Volta (VLTA)
-  Webasto (WEB)

As of the end of Q1, the ChargePoint network accounted for the largest number of public EVSE (43.2% of public EVSE) in the Station Locator, and Level 2 chargers comprised the majority of ChargePoint’s network (Fig. 10). This holds true for many of the networks in the Station Locator, except for the Electrify America, EVgo, and Tesla Supercharger networks, which are predominately, if not completely, made up of DC fast chargers.

![Figure 10. Breakdown of Public EVSE by Network and Charging Level in Q1.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-10.png)
**Figure 10. Breakdown of Public EVSE by Network and Charging Level in Q1.**

Fig. 11 shows the growth of each network in Q1, while Table 1 includes the percent growth of each network in Q1. The number of public EVSE on all networks grew in Q1. The Volta network experienced the largest growth in Q1, from 762 EVSE to 1,170 EVSE, which reflects 53.5% increase. This large increase is due to the previously mentioned spreadsheet update that NREL received from Volta in January 2020.

The FLO network was new to the Station Locator as of Q1 and is therefore excluded from Fig. 11 and Table 1. Additionally, there was only one EV charging station on the Francis network in the Station Locator at the end of 2019 Q4 and at the end of 2020 Q1, so the Francis network is also excluded from Fig. 11 and Table 1.

![Figure 11. Q1 Growth of Public EVSE by Network.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-11.png)
**Figure 11. Q1 Growth of Public EVSE by Network.**

**Table 1. Q1 Growth of Public EVSE by Network.**
<table cellpadding="0" cellspacing="0" style="margin-right: calc(9%); width: 91%;">
	<tbody>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center"><strong>Network </strong></p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center"><strong>Q1 Growth &nbsp;</strong></p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">NON&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">1.8%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">WEB&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">0.9%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">VLTA&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">53.5%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">TESLAD&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">0.2%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">TESLA&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">10.1%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">SCN&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">7.6%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">OC&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">0.0%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">GRN&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">24.2%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">EVN&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">3.2%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">EVC&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">17.7%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">EA&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">11.9%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">CPN&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">9.0%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center">BN&nbsp;</p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center">5.5%&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 50.6%;" valign="top">

				<p align="center"><strong>Total </strong></p>
			</td>
			<td style="width: 49.2%;" valign="top">

				<p align="center"><strong>7.6% </strong></p>
			</td>
		</tr>
	</tbody>
</table>


#### *2.1.3 By Region*
The Clean Cities Coalition Network is part of DOE’s Vehicle Technologies Office and works to advance alternative transportation fuels (including electricity), energy efficient mobility systems, and other fuel-saving technologies and practices in partnership with local stakeholders (Clean Cities Coalition Network, n.d.a.). The almost 100 local coalitions that make up the Clean Cities Coalition Network are comprised of businesses, fuel providers, vehicle fleets, state and local government agencies, and community organizations. The Clean Cities Coalition Network is broken down into regions (Fig. 12), which were used to analyze the growth of public EV charging infrastructure across the country (Clean Cities Coalition Network, n.d.b.).

![Figure 12. Clean Cities Regions.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-12.png)
**Figure 12. Clean Cities Regions.**

As shown in Fig. 13, the California region had the largest share of the country’s public EVSE in Q1 (31.8%), while the South Central region had the smallest share (8.0%). In Q1, the Northeast region experienced the largest growth in public EVSE (10.1%), and the North Central region experienced the smallest growth in public EVSE (4.1%) (Fig. 13).

![Figure 13. Q1 Growth of Public EVSE by Clean Cities Region.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-13.png)
**Figure 13. Q1 Growth of Public EVSE by Clean Cities Region.**

#### *2.1.4 By State*
To track the growth of EVSE by state, we calculated the number of public EVSE per 100,000 people in each state. We chose this metric to compare charging infrastructure development across states on a basis that accounts for proportional impact. Washington, D.C. is considered a state for the purpose of this analysis, and the population data used is based on the U.S. Census Bureau’s 2019 estimates (U.S. Census Bureau 2019).

As of the end of Q1, the number of EVSE per 100,000 people ranged from 4.8 in Alaska to 105.3 in Vermont. The five states with the highest number of EVSE per 100,000 people were Vermont, California, Washington, D.C., Hawaii, and Colorado (Table 2).

**Table 2. States with the Highest Rate of EVSE per 100,000 People.**
<table cellpadding="0" cellspacing="0" style="margin-right: calc(1%); width: 99%;">
	<tbody>
		<tr>
			<td style="width: 48.8971%;" valign="top">

				<p align="center"><strong>State </strong></p>
			</td>
			<td style="width: 50.9191%;" valign="top">

				<p align="center"><strong>EVSE per 100,000 People </strong></p>
			</td>
		</tr>
		<tr>
			<td style="width: 48.8971%;" valign="top">

				<p align="center">Vermont&nbsp;</p>
			</td>
			<td style="width: 50.9191%;" valign="top">

				<p align="center">105.3&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 48.8971%;" valign="top">

				<p align="center">California&nbsp;</p>
			</td>
			<td style="width: 50.9191%;" valign="top">

				<p align="center">64.0&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 48.8971%;" valign="top">

				<p align="center">Washington, D.C.&nbsp;</p>
			</td>
			<td style="width: 50.9191%;" valign="top">

				<p align="center">63.3&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 48.8971%;" valign="top">

				<p align="center">Hawaii&nbsp;</p>
			</td>
			<td style="width: 50.9191%;" valign="top">

				<p align="center">47.7&nbsp;</p>
			</td>
		</tr>
		<tr>
			<td style="width: 48.8971%;" valign="top">

				<p align="center">Colorado&nbsp;</p>
			</td>
			<td style="width: 50.9191%;" valign="top">

				<p align="center">40.9&nbsp;</p>
			</td>
		</tr>
	</tbody>
</table>

## 3 Private Charging Trends
Private EV charging refers to EV charging stations that are available only to certain drivers for specific purposes, such as charging for transit fleets or employee-only charging at places of work. While the Station Locator team proactively seeks out new station openings to include in the Station Locator, the opening of private workplace chargers may not necessarily be shared publicly. The Station Locator team therefore relies on Clean Cities coalitions, industry partners, and Station Locator users to share this information. Due to the challenge in collecting this data, the number of private, non-residential charging stations in the Station Locator is likely underrepresented.

In Q1, 434 new private EVSE were added to the Station Locator, bringing the total number of private EVSE in the Station Locator to 13,948 and representing a 3.2% growth from the end of 2019. The following sections break down the growth of private EVSE by level, as well as by two specific types: workplace charging and MUD charging.

### 3.1 By Charging Level
As shown in Fig. 14, the majority of private EVSE in the Station Locator are Level 2. However, DC fast EVSE experienced the greatest amount of growth overall (3.9%) in Q1 (Fig. 14). The private DC fast EVSE in the Station Locator are predominately for government fleets, including a few public transit authorities, or otherwise serve as workplace charging.

![Figure 14. Q1 Growth of Private EVSE by Charging Level.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-14.png)
**Figure 14. Q1 Growth of Private EVSE by Charging Level.**

### 3.2 Workplace Charging
Workplace EV charging infrastructure includes charging stations that are private and designated for employee use. The majority of private workplace EVSE in the Station Locator are Level 2 (Fig. 15). This is to be expected, since workplace chargers are used by employees while they are parked at work for an extended period and therefore do not necessarily need rapid charging As of the end of Q1, there were 7,967 workplace EVSE in the Station Locator. As shown in Fig. 15, DC Fast EVSE experienced the greatest amount of growth (5.9%) at workplaces.

![Figure 15. Q1 Growth of Private Workplace EVSE by Charging Level.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-15.png)
**Figure 15. Q1 Growth of Private Workplace EVSE by Charging Level.**

### 3.3 Multi-unit Dwelling Charging
In 2019, the Station Locator team began a focused effort to capture private charging infrastructure installed at MUDs that is available for resident use only. In Q1, there was a 9.3% increase in MUD EVSE, bringing the total number of private MUD EVSE to 364 (Fig. 16). All MUD EVSE in the Station Locator are either Level 1 or Level 2, but only Level 2 EVSE grew in Q1 (Fig. 16). Though the number of Level 2 EVSE increased by 10.0%, it is important to note that this represents an increase of 31 EVSE.

As the Station Locator team continues its concerted MUD data collection efforts in 2020, the number of MUD EVSE is likely to continue to grow.

![*Figure 16. Q1 Growth of Private MUD EVSE by Charging Level.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-16.png)
**Figure 16. Q1 Growth of Private MUD EVSE by Charging Level.**

### 3.4 Fleet Charging
In 2020, the Station Locator team will focus on expanding its private fleet data collection efforts, especially for fleets that are installing charging infrastructure for medium- and heavy-duty vehicles, such as school bus fleets and public transit fleets. Once a more robust dataset is available, future quarterly reports will include data on this kind of charging infrastructure.

## 4 Projecting Future Charging Infrastructure Needs
NREL’s 2017 “National Plug-In Electric Vehicle Infrastructure Analysis” estimated how much public and workplace EV charging infrastructure would be required in the United States in order to support a growing fleet of light-duty plug-in electric vehicles (PEVs) (Wood 2017). Based on a scenario in which there are 15 million light-duty PEVs on the road in 2030, this analysis estimated a total of 27,500 DC EVSE and 601,000 Level 2 EVSE would need to be available across the United States to meet demand for charging.

As of Q1, there were 13,627 public and workplace DC fast EVSE and 71,975 public and workplace Level 2 EVSE available in the United States (Fig. 17). Based on NREL’s 2017 analysis, the amount of DC fast and Level 2 EVSE installed is 49.6% and 12.0%, respectively, of the way toward meeting projected 2030 charging demand. However, it is important to keep in mind that 56.2% of public DC fast EVSE in the Station Locator are on the Tesla network and therefore only readily accessible to Tesla drivers.

![Figure 17. Current Availability and Projected Need of Public and Workplace Charging in the United States in 2030.](https://statics.bsafes.com/images/papers/electric-vehicle-charging-infrastructure-trends-from-the-alternative-fueling-station-locator-first-quarter-2020-fig-17.png)
**Figure 17. Current Availability and Projected Need of Public and Workplace Charging in the United States in 2030.**

## 5 Developments That Could Impact Future Quarters
The coronavirus pandemic and resulting restrictions and economic downturn is likely to have significant impacts on the development of EV charging infrastructure for the foreseeable future. As of April 2020, the EV charging industry has not been as hard hit as other areas of the energy sector, such as the oil industry, due to its smaller size and large investments from state and local governments, utilities, and OEMs (Ferris 2020). However, the shelter-in-place orders in place across the United States have resulted in a significant decline in vehicular travel and a decrease in demand for charging. The EVgo and Electrify America networks, for example, have seen charging sessions at their stations drop by more than 50% (Ferris 2020). Furthermore, vehicle production and sales have declined since the start of the pandemic as many OEMs, including General Motors, Ford, and Fiat Chrysler, temporarily closed their manufacturing plants in the United States in March in response to the pandemic (LeBeau 2020). However, Q1 EV sales fared better than the auto industry overall. Compared with the first quarter of 2019, total U.S. auto sales and U.S. EV sales declined by 12% and 0.8%, respectively, in Q1 (Cox Automotive 2020; EV Hub 2020).

Additionally, coronavirus restrictions have caused delays in the development of new EV infrastructure. Electrify America, for example, reported that construction of new charging stations had been delayed or halted at approximately 70% of its over 100 permitted station sites (Electrify America 2020). Based on this, we expect to see slower EV infrastructure growth in Q2 2020.

Despite the pandemic, state regulators continue to approve new utility electrification programs, including infrastructure development plans and customer incentive programs for chargers and PEVs (Ferris 2020). In addition, utilities continue to ramp up their existing incentive and rate programs. For example, Idaho Power is currently offering rebates for commercial customers who install charging stations between January 1, 2020, and November 15, 2020, for employee, fleet, or public use (Alternative Fuels Data Center, n.d.d.).

Finally, the Station Locator data collection and management processes will impact future EVSE counts. As noted in section 1.1.1, since 2019, the Station Locator team has been transitioning its counting logic to align with the hierarchy defined in the OCPI protocol: locations, EVSE, and connectors (EVRoaming Foundation, n.d.). With this transition, the Station Locator is now counting the number of EVSE at a station location rather than the number of connectors previously counted. For example, a charging location with one EVSE and two connectors was previously counted twice but is now only counted once using the OCPI protocol’s counting logic. As of Q1, all manually collected data, as well as EVSE on the Electrify America and EVgo networks, are counted according to the OCPI logic. NREL is currently working with Greenlots and ChargePoint to integrate their OCPI APIs into the Station Locator.

As discussed in section 1.1.1., NREL is continuously working with EVSPs to add new APIs to the Station Locator. As these new APIs come online, there will likely be a large increase in the number of EVSE in the Station Locator.

## 6 Conclusion
This paper sets a baseline for tracking various EV infrastructure growth trends moving forward, including the growth of public EV charging by charging level, network, region, and state, and the growth of private EV charging by charging level and use type (i.e., workplace and MUD). With such rapid growth and change in EV charging infrastructure, the information presented in this paper aims to help readers understand how and where the infrastructure is developing, where there may be areas of opportunity, and whether development is keeping pace with the projections of demand for charging as the number of EVs on the road continues to grow.

As of the end of Q1, Level 2 chargers accounted for the majority of both public and private EVSE in the Station Locator. However, based on the projected number of public and workplace Level 2 chargers required to meet charging demand in 2030, the number of Level 2 EVSE currently available still falls significantly short (Wood 2017). The number of public and workplace DC fast EVSE, on the other hand, is just under halfway toward meeting NREL’s projection, and in Q1, both public and private DC fast EVSE grew by the greatest percentage. Additionally, the number of public DC fast EVSE with power output above the standard 50 kW grew significantly more than DC fast EVSE with power output at or below 50 kW. However, the majority of public DC fast EVSE in the Station Locator are on the Tesla network and therefore only readily accessible to Tesla drivers.

California continues to lead the country in terms of the total public EVSE available and only drops slightly in rank, to second, when compared to other states based on EVSE available per 100,000 people. Additionally, the California region experienced the second largest growth of public EVSE in Q1, behind the Northeast region.

If there are additional metrics that readers are interested in seeing, please email suggestions to the authors at TechnicalResponse@icf.com.

## Bibliography
Alternative Fuels Data Center. n.d.a. “About the Alternative Fuels Data Center.” Accessed June 5, 2020. https://afdc.energy.gov/about.html.

Alternative Fuels Data Center. n.d.b. “Alternative Fueling Station Locator.” Accessed June 5, 2020. https://afdc.energy.gov/stations/#/find/nearest.

Alternative Fuels Data Center. n.d.c. “Data Included in the Alternative Fueling Station Data.” Accessed June 5, 2020. https://afdc.energy.gov/data_download/alt_fuel_stations_format. 

Alternative Fuels Data Center. n.d.d. “Commercial Electric Vehicle Supply Equipment (EVSE) Incentive – Idaho Power.” Accessed June 5, 2020. https://afdc.energy.gov/laws/12396.

Clean Cities Coalition Network. n.d.a. “About Clean Cities.” Accessed June 5, 2020. https://cleancities.energy.gov/about/.

Clean Cities Coalition Network. n.d.b. “Technology Integration Program Contacts.” Accessed June 5, 2020. https://cleancities.energy.gov/contacts/?open=regional#headingregionalManagers. 

Cox Automotive. 2020. “10 Takeaways from U.S. Auto Sales: Q1 2020 and COVID-19.” *Cox Automotive*, April 9, 2020. https://www.coxautoinc.com/market-insights/10-takeaways-from-u-sauto-sales-q1-2020-and-covid19/?utm_source=EV+Hub+Newsletter&utm_campaign=279c75644cEMAIL_CAMPAIGN_2019_01_07_05_37_COPY_01&utm_medium=email&utm_term=0_173e047b1f279c75644c246816833. 

Electrify America. 2020. *2019 Annual Report to the U.S. EPA: Public Version.* April 30, 2020. https://newspress-electrifyamerica.s3.amazonaws.com/documents%2Foriginal%2F419-2019ElectrifyAmericaNationalAnnualReport.pdf.

EV Hub. 2020. “U.S. EV Sales Flat Through First Quarter.” *EV Hub Weekly Digest,* June 8, 2020. 

EVRoaming Foundation. 2019. *OCPI 2.2: Open Charge Point Interface.* Document Version 2.2, September 30, 2019. https://ocpi-protocol.org/app/uploads/2019/10/OCPI-2.2.pdf. 

Ferris, David, and David Iaconangelo. 2020. “The future was supposed to be electric. Is it still?” E&ENews, April 16, 2020. https://www.eenews.net/stories/1062876693?utm_term=0_173e047b1f-094d8adbde-246816833. 

LeBeau, Phil, and Noah Higgins-Dunn. 2020. “General Motors, Ford and Fiat Chrysler to temporarily close all US factories due to the coronavirus.” *CNBC,* March 18, 2020. https://www.cnbc.com/2020/03/18/general-motors-ford-and-fiat-chrysler-to-close-all-usfactories-due-to-the-coronavirus-sources-say.html.

Levene, Johanna, Stephen Lommele, Robert Eger, and Wendy Dafoe. 2019. “Developing a Comprehensive Database of Alternative Fuel Station Locations across Canada and the United States of America.” In Canadian Transportation Research Forum 54th Annual Conference Proceedings, 2019.

U.S. Census Bureau. 2019. “NST-EST2019-01: Table 1. Annual Estimates of the Resident Population for the United States, Regions, States, and Puerto Rico: April 1, 2010 to July 1, 2019.” Accessed June 5, 2020. https://www.census.gov/newsroom/press-kits/2019/national-stateestimates.html. 

Wood, Eric, Clément Rames, Matteo Muratori, Sesha Raghavan, and Marc Melaina. 2017. *National Plug-In Electric Vehicle Infrastructure Analysis.* Golden, CO: National Renewable Energy Laboratory. https://www.nrel.gov/docs/fy17osti/69031.pdf.

</div>

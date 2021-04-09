---
layout: default
title: 3 Non-Residential L2 and DCFC for Community Charging
parent: § National Plug-In Electric Vehicle Infrastructure Analysis 
grand_parent: Electric Vehicle
has_children: itrue
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

## 3 Non-Residential L2 and DCFC for Community Charging
Most driving in the United States consists of habitual trips in and around the communities where people live, making convenient access to charging in these communities crucial to widespread PEV adoption. Although the majority of PEV charging currently takes place at home, access to charging away from home at long dwell time locations, commercial entities, and along freeways is highly valued by drivers as it dispels range anxiety and enables a greater share of electric miles. The analysis in this section estimates charging requirements in cities, towns, and rural areas to support the growing PEV market. First, coverage estimates are made for a minimum level of DCFC stations within cities and towns to support BEV intra-city long distance travel and emergency situations such as failing to charge overnight at home. Next, the National Renewable Energy Laboratory’s (NREL’s) Electric Vehicle Infrastructure Projection (EVI-Pro) tool is used to estimate nonresidential charging requirements for a baseline scenario of 15 million PEVs on U.S. roads in 2030. Finally, a sensitivity analysis is presented to document model uncertainty with respect to key factors such as technology development, PEV market evolution, and consumer charging behavior.

### 3.1 DCFC Coverage Estimates
This section presents a straightforward approach to estimating the number of DCFC stations required to provide minimum coverage for PEVs in cities and towns. L2 station coverage is not considered, assuming that non-residential L2 is primarily used for charging within walking distance of a destination (based on the low charge power and long charge time of L2 stations), and coverage for every destination is unrealistic for the early PEV market. Coverage estimates are also omitted for DCFC stations in rural areas, because coverage provided by stations in cities/towns and along interstate corridors (see Section 4) is deemed to be sufficient. Given that PHEVs are assumed to perform most charging at home and can use an internal combustion engine for backup power, they are naturally excluded from this calculation of a minimum charging coverage requirement. Consequently, attention is paid to DCFC stations supporting BEVs in cities and towns.

As a simplifying assumption, coverage estimates assume DCFC stations are spaced uniformly on a square grid across a two-dimensional area within each community. For BEV drivers to never be more than 3 linear miles from a DCFC station in a given city, 56 stations per 1,000 square miles would be required (for reference, there are currently 960 gasoline stations per 1,000 square miles in U.S. cities). This station density is applied to the 108,246 square miles occupied by cities and towns in the United States, resulting in a national DCFC station count of 8,072 (4,861 in cities and 3,211 in towns).

For comparison, the public DCFC station density per 1,000 square miles in major PEV markets ranges from 16 in New York and 17 in Chicago to 130 in San Jose and 155 in San Francisco (as of June 2017). The average DCFC density per 1,000 square miles in the top 10 U.S. PEV markets is 65. This number drops to 18 across all cities and towns nationwide.

### 3.2 Non-Residential EVSE Community Demand Estimates
This section describes methods for estimating non-residential EVSE (work L2, public L2, and public DCFC) demand requirements for community charging. NREL has developed three regional models using EVI-Pro— for California, Massachusetts (Wood et al. 2017), and the Columbus, Ohio, area (Wood et al. forthcoming). The findings from those models are extended to estimate nominal ratios of EVSE per 1,000 PEVs for the national study. These nominal ratios are adjusted for the various communities across the United States. Adjustments to the nominal EVSE/PEV ratios are based on population density, PEV concentration, and local ambient temperature.

PEV stock for all communities (486 cities, 3,087 towns, and 50 rural areas with state-level aggregation) is calculated by disaggregating a national PEV count (15 million in the baseline 2030 scenario) proportionally to existing registration data from IHS Markit. Three variations on PEV disaggregation are considered based on: 1) all existing LDV registrations, 2) existing HEV registrations, and 3) existing PEV registrations. Among these three options, basing disaggregation on existing PEV registrations maximizes the number of PEVs in cities and ZEV states, whereas basing it on existing LDV registrations places a comparatively larger share of PEVs in towns, rural areas, and non-ZEV states (see Section 2). Basing disaggregation on existing HEV registrations produces results that are in between the results of the other two approaches in terms of geographic PEV distribution. The central scenario uses the HEV-based disaggregation approach, and the other approaches are used for sensitivity analysis.

After individual EVSE/PEV ratios and PEV stocks for each geography are calculated, the ratio and stock values are simply multiplied to generate a localized estimate of consumer demand for non-residential charging. A schematic of this approach is shown in Figure 5.

![Figure 5. Schematic for estimating community charging requirements.](https://statics.bsafes.com/images/papers/national-plug-in-electric-vehicles-infrastructure-analysis-fig-5.png)
**Figure 5.** Schematic for estimating community charging requirements.

_(Satellite imagery credit: © 2017 Google, Map Data © 2017 Tele Atlas)_

#### 3.2.1 Electric Vehicle Infrastructure Projection (EVI-Pro) Tool
Consumer demand for non-residential L2 and DCFC is estimated using EVI-Pro. NREL developed EVI-Pro in partnership with the California Energy Commission to estimate regional requirements for charging infrastructure that supports consumer adoption of light-duty PEVs. EVI-Pro uses real-world travel data to simulate spatially and temporally resolved demand for PEV charging at homes, workplaces, and public destinations. It anticipates consumer charging behavior while capturing variations with respect to housing type (single- versus multi-unit dwellings [MUDs]), travel period (weekdays versus weekends), and regional differences in travel behavior and vehicle adoption. Its fundamental assumption is that consumers prefer charging scenarios that enable them to complete all their existing travel with maximum eVMT and minimum operating cost. For more information about EVI-Pro’s functionality, see the methodology section of Wood et al. (2017).

#### 3.2.2 Estimating Non-Residential EVSE/PEV Nominal Ratios
A mix of PEVs selected to emulate the 2030 PEV market is shown in Table 4. EVSE attributes assumed for charging infrastructure are summarized in Table 5.

**Table 4.** Modeled Vehicles
![Table 4. Modeled Vehicles](https://statics.bsafes.com/images/papers/national-plug-in-electric-vehicles-infrastructure-analysis-table-4.png)

**Table 5.** Modeled Charging Infrastructure
![Table 5. Modeled Charging Infrastructure](https://statics.bsafes.com/images/papers/national-plug-in-electric-vehicles-infrastructure-analysis-table-5.png)
***

L1 = level 1 charging station

***

Global positioning system travel trajectories for the Columbus area from commercial traffic/mapping provider INRIX were used as the input data set to the EVI-Pro model (Wood et al. forthcoming). Results from the Columbus model were harmonized with PEV/EVSE ratios from the California model (based on the 2012 California Household Travel Survey) and Massachusetts model (based on the 2011 Massachusetts Travel Survey). This process yields a nominal set of EVSE/PEV ratios for each charger location and power level. Figure 6 shows the nominal EVSE/PEV ratios in terms of plugs per 1,000 PEVs for work L2, public L2, and public DCFC infrastructure. These estimates assume a home-dominant charging pattern in which consumers have access to home charging and prefer to do most charging at home owing to their electricity rate structures and the perceived level of convenience.

![Figure 6. Nominal non-residential EVSE/PEV ratios (home dominant charging behavior).](https://statics.bsafes.com/images/papers/national-plug-in-electric-vehicles-infrastructure-analysis-fig-6.png)
**Figure 6.** Nominal non-residential EVSE/PEV ratios (home dominant charging behavior).

The relationship between electric range and estimated infrastructure requirements is clear in these results. PEVs with longer electric ranges are less dependent on work and public charging to maximize eVMT (e.g., the BEV250 results in almost non-existent L2 charging requirements at work and public locations). Because PHEVs are incompatible with fast charging in this analysis, by definition they have no DCFC requirements.

The resulting charging load profile from home-dominant EVI-Pro simulations is shown in Figure 7. Note that 88% of charging in the EVI-Pro simulations is from residential EVSE (either L1 or L2). The simulations do not account for electricity pricing mechanisms or consumer incentives (such as time-of-use pricing) designed to shift load from the early evening into overnight hours. These effects have significant impacts on the operation of the electricity grid, but do not impact the non-residential EVSE/PEV ratios estimated in this report.

![Figure 7. Nominal charging load profile from EVI-Pro simulations (home dominant charging behavior).](https://statics.bsafes.com/images/papers/national-plug-in-electric-vehicles-infrastructure-analysis-fig-7.png)
**Figure 7.** Nominal charging load profile from EVI-Pro simulations (home dominant charging behavior).

The nominal set of EVSE/PEV ratios is adjusted to account for the unique characteristics of all U.S. geographies based on population density, PEV concentration, and ambient temperature, as discussed in Appendix .

#### 3.2.3 National Results in the Central Scenario
A set of national simulations is run using the settings from the central scenario (discussed in Section 1.2.2). Table 6 shows the modeled estimates for PEVs and EVSE for the top 10 urban areas from simulation of the central scenario. Results by community type and national totals are shown in Table 7, and state-level results are shown in Appendix . In 2030, approximately 600,000 L2 plugs (work and public) and 25,000 DCFC plugs are projected to serve 15 million PEVs across the United States. These estimates normalize to 40 L2 plugs per 1,000 PEVs and 1.7 DCFC plugs per 1,000 PEVs.

Present day public charging infrastructure represents approximately 13% of the plug count estimates modeled for 2030 (under PEV market assumptions in the central scenario). However, cities such as San Jose, California (73%), San Francisco, California (43%), and Seattle, Washington (41%) are much closer to the estimated requirements for the 15 million PEVs simulated in the central scenario.

**Table 6.** Central Scenario PEV and Non-Residential EVSE Estimates in 2030, Top 10 Urban Areas
![Table 6. Central Scenario PEV and Non-Residential EVSE Estimates in 2030, Top 10 Urban Areas](https://statics.bsafes.com/images/papers/national-plug-in-electric-vehicles-infrastructure-analysis-table-6.png)

**Table 7.** Central Scenario PEV and Non-Residential EVSE Estimates in 2030, by Community Type (with National Total)
![Table 7. Central Scenario PEV and Non-Residential EVSE Estimates in 2030, by Community Type (with National Total)](https://statics.bsafes.com/images/papers/national-plug-in-electric-vehicles-infrastructure-analysis-table-7.png)

#### 3.2.4 Sensitivities of National Results to Various Assumptions
This section illustrates the sensitivity of the national results to potentially important assumptions. Figure 8 shows the results in terms of total national plug requirements, whereas Figure 9 shows the results in terms of normalized requirements (EVSE/PEV ratios). For example, increasing the number of PEVs from the central value of about 15 million to 21 million increases the number of non-residential L2 plugs from 600,000 to 820,000, and it increases the number of DCFC plugs from 25,000 to 33,000 (Figure 8). The effects of changing PEV penetration are smaller on a normalized basis, especially for non-residential L2 plugs. Otherwise, the ranking of influential variables is similar for total and normalized non-residential L2 plugs: 1) PHEV support, 2) range preference, 3) percent home charging, 4) PHEV:BEV ratio, 5) percent of PEVs cities, and 6) SUV share. For DCFC plugs, PHEV support has no impact as PHEVs are not modeled as supporting DCFC. Range preference has the largest impact, followed—on a normalized basis—by percent home charging, PHEV:BEV ratio, PEV count, and percent of PEVs in cities.

This analysis also enables comparison of the input variables’ impacts on the L2 and DCFC total plug counts. Supporting PHEVs boosts L2 plug counts significantly since PHEVs are modeled as using non-residential L2 EVSE at significantly higher rates than BEVs, whereas it has no effect on DCFC plug counts as PHEVs cannot use DCFC. Similarly, a high ratio of PHEVs to BEVs favors L2 EVSE, and a high ratio of BEVs to PHEVs favors DCFC. The need for both power levels rises as the range of PEVs declines, since shorter-range PEVs require more non-residential charging. The need for both types of charging infrastructure decreases as the share of PEVs in cities increases, because daily average vehicle miles traveled (VMT) is lower in denser urban areas (see Appendix B). More home charging also reduces the need for both types of charging infrastructure.

![Figure 8. Effects of input variables on estimated total national plug requirements.](https://statics.bsafes.com/images/papers/national-plug-in-electric-vehicles-infrastructure-analysis-fig-8.png)
**Figure 8.** Effects of input variables on estimated total national plug requirements.

![Figure 9. Effects of input variables on normalized national plug requirements (EVSE/PEV ratios).](https://statics.bsafes.com/images/papers/national-plug-in-electric-vehicles-infrastructure-analysis-fig-9.png)
**Figure 9.** Effects of input variables on normalized national plug requirements (EVSE/PEV ratios).

</div>

---
layout: default
title: APPENDIX H – ALL HAZARDS ANALYSIS (AHA)      
parent: § Jack Voltaic 3.0 Cyber Research Report 
grand_parent: Internet
nav_order: 150 
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

1. TOC
{:toc}

## APPENDIX H – ALL HAZARDS ANALYSIS (AHA)
Idaho National Laboratory’s (INL’s) AHA tool is a hybrid data and expert knowledge management system that enhances situational awareness and decision making by enabling the development of function-based infrastructure dependency models. The INL team supported the JV 3.0 and Jack Pandemus exercises by using its AHA tool to process open-source government information, regulatory information, and other publicly available data to develop dependency models for the Charleston and Savannah regions, and then performing dependency analyses for these regions. INL created an instance of AHA for the JV exercises and loaded the results of the analysis into it. The JV instance of AHA was utilized to create cascading-impact scenarios that highlighted downstream impacts resulting from the degraded operations at various infrastructure in the energy and water sectors. Scenarios depicting how the regions’ infrastructure are connected and how they were subsequently impacted by the various injects were captured in PowerPoint presentations and videos, which were then utilized in the exercises.

### H.1. Charleston Exercise Findings
INL supported the energy sector table for the Charleston exercise by supplementing the discussion with pointed questions to the owners and operators from the energy sector. The intent was to facilitate a dialogue to identify how the various stakeholders would respond to the situations presented within each turn. The players from the energy sector did not seem to believe the injects would have a debilitating impact on their operations. This could have been rectified through interacting more with the stakeholders prior to the workshop as well as focusing on the bulk transmission of energy versus the distribution aspects.

The injects in which the electricity substation was compromised resulted in some discussion during the Charleston exercise; however, utility participants thought they would be able to work around the issue. INL believes this was due to a lack of clarity in the scale of the event and language used. If AHA results were shown, INL believes participants’ responses would have been altered. It was not clear from the discussion how Dominion Energy tests firmware configuration changes. Notes of interest included:

- On multiple occasions, a utility participant expressed that someone else within their organization would be responsible for determining whether they were experiencing a cyberattack. 

- The Charleston energy table participants never reached the conclusion they were under attack. As stated below, the advisory/alert and phishing threads played almost no role in the discussion. 

- The virtual environment resulted in some challenges getting injects out of DECIDE® and inserted into the discussion. As a result, the moderator summarized each inject at the being of each turn. 

- Some discussion occurred on the segregation of control and business networks—specifically, which computers were impacted. Participants believed the computer-based injects implied business system computers (i.e., IT, not OT). 

- Local workarounds discussed included disconnecting control devices and operating in manual mode. 

- Participants did not have concerns about being able to access the substation.

### H.2. Savannah Exercise Findings
INL supported the energy table in the Savannah exercise by supplementing the discussion with pointed questions to the owners and operators from the energy sector. The intent was to facilitate dialogue to identify how the various stakeholders would respond to the situations presented within each turn. The JV instance of AHA was leveraged during the exercise to help participants visualize the infrastructure being discussed during each turn. This seemed to assist with getting the injects to resonate with the participants and teasing out additional context that likely would not have otherwise been discussed.

The inject involving a compromise of natural gas compressor station firmware resulted in significant discussion during the Savannah exercise. The Savannah participants had a mix of cybersecurity and engineering representatives who were able to piece the scenario together. In addition, showing results from AHA resulted in a quick realization that this was a significant event and would result in significant interruptions in service. The cybersecurity representatives quickly picked up on the scene setter injects, which resulted in in-depth gameplay discussions. However, some participants were confused by language used in the inject to describe the events taking place. Notes of interest included:

- Cybersecurity personnel were actively engaged and cyber compromise was rapidly considered. 

- Local workarounds including disconnecting control devices and operating in manual mode. 

- Participants had no concerns about being able to access the substation. Participants discussed potentially involving company security personnel in the response.

Figure 26: Excerpt from Turn 5 PowerPoint Slide—Natural Gas Compressor Stations

### H.3. Lessons Learned
*Inject planning:* INL supported the development of the injects utilized throughout the turns of the JV exercises. By the time the INL team was brought in to support this area, the inject planning was in progress and the development of the Master Scenario Event List (MSEL) was already underway. If the AHA simulation had been involved from the initial stages of planning, the turns and injects could have allowed for a more robust scenario. Analysis of downstream infrastructure and the associated impacts in the event operations became degraded would identify potential assets that may not have been identified in the JV 3.0 exercises.

*Obfuscation of infrastructure names:* Throughout the process of developing the infrastructure to be included in the scenario, the INL team obfuscated the names of the assets in the JV instance of AHA. This was performed under the assumption the exercise needed to be agnostic regarding the actual infrastructure within the Charleston and Savannah regions. As the exercise played out, it became clear the scenario resonated more with the stakeholders when the actual infrastructure names were used in describing where the events of the scenario were occurring.

*Interaction with service providers:* The primary interaction the INL team had with the service providers involved in the exercise was during the exercise itself. The dialogue with the service providers uncovered nuances about their operations that would have been beneficial to know during inject planning. A brief interaction occurred during the rehearsal sessions, but that discussion was mainly focused on the water sector. During the actual exercise, INL supported the energy table and did not have any direct interaction with the water sector.

Earlier engagement with service providers would allow for better understanding of the presence—or lack thereof—of alternate sources of critical products required for operations. This bottom-up level of detail would allow for more tailored scenario planning that could reveal supply chain issues that may only arise when alternate modes of operations are being leveraged.

*Use of terminology and focus areas:* The primary focus of the impacts on the energy sector during the scenario was on the infrastructure involved with the distribution of the commodity (i.e., distribution substations or distribution pipelines). Impacts on these infrastructure resonate with the downstream asset owners who are depending on the commodity being provided, but the service providers were generally able to rectify the consequences of impacts at this level fairly quickly by either switching to manual operations or redirecting the load to a different set of distribution infrastructure. If the focus area of the impacts were to be shifted to the bulk transport of commodities (i.e., transmission substations or compressor stations), the impacts would be on a broader scale, but the response by the service providers to control the impact would not be as easily identifiable. Consideration should be given to transmission infrastructure in planning future injects and scenarios.

</div>

---
layout: default
title: 3. INTRODUCTION - JACK VOLTAIC 3.0 
parent: § Jack Voltaic 3.0 Cyber Research Report 
grand_parent: Internet
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

1. TOC
{:toc}

## 3. INTRODUCTION: JACK VOLTAIC 3.0

### 3.1. Fictional Crisis
*An international crisis in Europe prompts the President to order the rapid deployment of a brigade combat team as a show of force in support of U.S. allies. Forces are needed immediately, and any delay would further harm U.S. and North Atlantic Treaty Organization interests. As the United States begins to transport equipment from their forts to strategic ports, its adversaries begin a cyber assault on the domestic civilian-owned critical infrastructure that supports and facilitates such movement. The cyber assault starts with small, seemingly unconnected incidents: The port’s gates begin having small malfunctions, several organizations experience minor issues with their administrative systems, and reports of a new phishing campaign surface. These small incidents soon give way to larger ones that cascade across critical infrastructure sectors and significantly tax local responders. While the public and private sectors respond to these multiple incidents, the brigade combat team’s equipment is caught in the middle. The brigade combat team commander is closely monitoring the movement of the unit’s equipment, but the commander realizes he or she must consider the possibility that the equipment may not arrive at the destination in time to effectively execute the current plan.*

Adversarial competitors are increasingly leveraging cyber activities to gain strategic advantage over the United States, partner nations, and global industry using targeted espionage and attacks against all elements of critical infrastructure. For example, in February 2020, the United States Computer Emergency Readiness Team issued an advisory that a cyber threat actor had used a spear-phishing link to obtain access first to a natural gas company’s information technology (IT) network, and then to its operational technology (OT) network. Next, the threat actor deployed commodity ransomware to encrypt data for impact on both networks. The company never lost control of its operations but still decided to implement a shutdown. Although the direct operational impact of the cyberattack was limited to one control facility, other facilities had to halt operations because of pipeline transmission dependencies, resulting in an operational shutdown of the entire pipeline that lasted about 2 days.<sup>1</sup>

The 2015 *Department of Defense Cyber Strategy* states, “In addition to DoD’s own networks, a cyberattack on the critical infrastructure and key resources on which DoD relies for its operations could impact the U.S. military’s ability to operate in a contingency.”<sup>2</sup> The Department of Defense Cyber Strategy 2018 Summary states that the DoD “must be prepared to defend non-DoD-owned Defense Critical Infrastructure (DCI) and Defense Industrial Base (DIB) networks and systems. [The DoD’s] chief goal in maintaining an ability to defend DCI is to ensure the infrastructure’s continued functionality and ability to support DoD objectives in a contested cyber environment.”<sup>3</sup> The strategy document goes on to say that “the DoD will work with its interagency and private sector partners to reduce the risk that malicious cyber activity targeting U.S. critical infrastructure could have catastrophic or cascading consequences.”<sup>4</sup>

***
<sup>1</sup> Alert (AA20-049A): Ransomware Impacting Pipeline Operations,” United States Computer Emergency Readiness Team (website), updated October 24, 2020, https://us-cert.cisa.gov/ncas/alerts/aa20-049a.
{: .fs-2}
<sup>2</sup> Department of Defense (DoD), *The Department of Defense Cyber Strategy* (Washington, DC: DoD, April 2015), 10.
{: .fs-2}
<sup>3</sup> DoD, *The Department of Defense Cyber Strategy 2018 Summary* (Washington, DC: DoD, September 2018), 3.
{: .fs-2}
<sup>4</sup> DoD, *Cyber Strategy 2018 Summary*, 5.
{: .fs-2}
***

United States Cyber Command also highlights this critical guidance within its overarching imperatives. Imperative 5 outlines the need to “expand, deepen, and operationalize partnerships” in ways that “leverage the talents, expertise, and products in the private sector, other agencies, Services, allies, and academia.”<sup>5</sup> The strategic importance of ensuring domestic critical infrastructure resilience is further reinforced by the National Cyber Strategy of the United States of America’s pillar 1 (“Protect the American People, the Homeland, and the American Way of Life”) in which “Secure Critical Infrastructure” is presented as a crucial component.<sup>6</sup> More recently, the second strategy layer (“Deny benefits”) in the Cyberspace Solarium Commission Final Report emphasized this importance as well, stating, “National resilience efforts rely on the ability of the United States, in both the public and private sectors, to accurately identify, assess, and mitigate risk across all elements of critical infrastructure.”<sup>7</sup>

The ACI’s JV research project supports the 2015 and 2018 DoD Cyber Strategies while aligning with elements of the United States Cyber Command Vision, National Cyber Strategy, and *Cyberspace Solarium Commission Final Report*’s layer-two strategic approach through the analysis of critical infrastructure resiliency, cyber incident response, and public-private partnerships. This concept grew from the energy sector’s efforts to develop cyber mutual assistance, supporting sector coordination and resourced responses to major cyber incidents.<sup>8</sup> When an incident occurs, such as a natural disaster that causes a power outage, cyber mutual assistance ensures that assets and capabilities from across the Nation come together to provide response and recovery. JV expands this concept across multiple critical infrastructure sectors because the cyber domain innervates all sectors, creating various types of dependencies.

The JV research project enables the ACI to study incident response gaps alongside assembled partners to identify interdependencies among critical infrastructure and provide recommendations. JV provides an innovative, bottom‐up approach to critical infrastructure resilience in two unique ways. Whereas most federal efforts to improve resiliency focus on regional or multistate emergency response, JV focuses on cities and municipalities where critical infrastructure and populations are most heavily concentrated. Furthermore, JV deviates from other cybersecurity and national preparedness exercises by building around areas of interest nominated by the participants. Although JV events include national-level capabilities and resources, they are conceptually driven by the concerns of the cities and their infrastructure partners. Through this approach, the ACI, the Army, and the DoD are able to gather unique insights about potential roles, dependencies, partners, and support requests, while cities are able to discover potential capability gaps and expand their critical infrastructure information-sharing networks before a potential disaster strikes.

***
<sup>5</sup> United States Cyber Command, *Achieve and Maintain Cyberspace Superiority: Command Vision for US Cyber Command* (Fort Meade, MD: United States Cyber Command, April 2018), 9.
{: .fs-2}
<sup>6</sup> Donald J. Trump, *National Cyber Strategy of the United States of America* (Washington, DC: The White House, September 2018), 8–10.
{: .fs-2}
<sup>7</sup> U.S. Cyberspace Solarium Commission, *Cyberspace Solarium Commission Final Report* (Washington, DC: U.S. Cyberspace Solarium Commission, March 2020), 4
 {: .fs-2}
<sup>8</sup> Jonathon Monken et al., *Cyber Mutual Assistance Workshop Report* (Pittsburgh, PA: Carnegie Mellon University Software Engineering Institute, 2018), https://resources.sei.cmu.edu/asset_files/SpecialReport/2018_003_001_513596.pdf.
{: .fs-2}
***

This bottom-up approach identifies key stakeholders and public-private partnerships, experimental design elements, governance hierarchies, exercise simulations, and relevant data collection points to elucidate critical insights into incident response gaps, vulnerabilities, as well as strengths.<sup>9</sup> The overarching research goals of the JV research series are:

- Identifying a repeatable and scalable framework usable by any city to rehearse responses to cyber events that affect multiple sectors and require coordinated responses. 

- Providing a safe learning environment that enables participants to receive training on, assess, and gain exposure to and an appreciation for cyber, physical, and cyber-enabled physical incidents. 

- Increasing communication between leadership and their technical teams and among organizations from different sectors. 

- Improving information sharing and response coordination among municipalities; county, state, federal, and tribal organizations; industry; and the private sector. 

- Providing DoD data, information, and feedback to validate planning assumptions and maintain readiness.

The ACI has conducted JV research for the past 4 years and, in that time, completed three experiments in the form of cyber exercises: JV 1.0 in New York City (NYC) from August 29 through 31, 2016; JV 2.0 in Houston from July 24 through 26, 2018; and JV 3.0 in Charleston on September 22, 2020, and in Savannah on September 24, 2020. In addition to these four events, the ACI held the JV 2.5 Cyber Workshop Series in the port cities of San Diego, Tacoma, San Francisco, Savannah, Charleston, Augusta, and Norfolk in summer 2019.

JV 3.0 leveraged the JV approach to allow the ACI to gain insight into how multiple levels of industry and government respond to a cyberattack against local, commercial, and federal critical infrastructure that supports Army force projection operations—specifically, critical infrastructure in port cities from which Army personnel and equipment would deploy in the case of a military conflict overseas.<sup>10</sup> In parallel with the Army’s Defender 2020<sup>11</sup> force projection exercise, JV 3.0 examined and analyzed the ability of Charleston, South Carolina (SC), and Savannah, Georgia (GA)—two major port cities on the East Coast— to support force projection in the face of cyber aggression against all aspects of geographically aligned critical infrastructure.<sup>12</sup>

Originally planned as a 3-day event in April 2020 held simultaneously in these two port cities, the ACI decided to make JV 3.0 two single-day, virtual events—one for Charleston and one for Savannah— because of complications arising from the COVID-19 pandemic. Stakeholders from the two cities and states as well as public and private partners still participated in the virtual exercises using the Distributed Environment for Critical Infrastructure Decision-making Exercise (DECIDE®) platform and Microsoft Teams. Participants included representatives from the transportation, energy, emergency management, communications, information technology (IT), government facilities, and water/wastewater sectors.

***
<sup>9</sup> Erica Mitchell et al., Jack Voltaic Critical Infrastructure and Public-Private Partnerships (West Point, NY: United States Military Academy, July 18, 2019), 9.
{: .fs-2}
<sup>10</sup> Mark Pomerleau, “How the Army Is Strengthening Cyber Cities,” Fifth Domain, July 30, 2019, https://www.fifthdomain.com/dod/army/2019/07/30/how-the-army-is-strengthening-cyber-cities/.
{: .fs-2}
<sup>11</sup> “DEFENDER-EUROPE 20,” Supreme Headquarters Allied Powers Europe (website), n.d., https://shape.nato.int/defender-europe, accessed December 29, 2020. 
{: .fs-2}
<sup>12</sup> Shannon Vavra, “US Army Combines Fake Hacks, Natural Disaster Simulation to Test Municipal Responses,” Cyberscoop, September 24, 2020, https://www.cyberscoop.com/army-savannah-charleston-cyber-test/.
{: .fs-2}
***

When designing the scenario, the ACI and stakeholders based the scenario on real-life incidents to simulate a series of small, seemingly unrelated events instead of a single, catastrophic event. This “death by a thousand cuts” approach relied on the aggregation of all the events across the different sectors to create a situation that overcommitted local response resources in both cities. As a result, the scenario reinforced a whole-ofcommunity approach to cyber incident response and critical infrastructure resiliency. It allowed participants to observe the responses of other participants and identify organizations and sectors with which they should communicate, thereby laying the groundwork for increased collaboration.

### 3.2. Origin and History of Jack Voltaic

#### 3.2.1. Cyber Mutual Assistance Workshop (CMAW) 
On April 8, 2016, the ACI conducted the initial phase of the JV research project, the Cyber Mutual Assistance Workshop (CMAW).<sup>13</sup> The workshop was led and facilitated by the ACI, the Electric Infrastructure Security Council, and Carnegie Mellon University. The CMAW provided an opportunity for practitioners and experts from the public and private sectors to examine cyber mutual assistance using a holistic approach and to share capabilities and issues concerning the energy sector.

During the CMAW, the ACI used a cyber exercise to examine mutual assistance from the angles of preparation, prevention, and response. The research objectives of the CMAW were: 

- Define capability requirements for cyber;
- Discuss existing legal and operational frameworks;
- Develop partnerships;
- Develop a multisector exercise; and
- Define and plan a follow-on experiment to examine interdependencies among critical infrastructure sectors.

#### 3.2.2. JV 1.0 
JV 1.0 was a 2-day event in NYC in August 2016 that simulated a cyberspace attack impacting multiple sectors and exercised the city’s ability to respond to such an attack.<sup>14</sup> JV 1.0 simulated a hypothetical cyber event involving a strategic, methodical attack occurring over 6 days. The first phase of the attack impacted the financial sector through a spear-phishing attack targeting a financial executive. In the second phase, the malicious actor targeted the energy sector by installing malicious software on a power company’s network. The malware granted control of the company’s power stations to the attacker, who used them as a pivot point to further exploit and compromise the city’s transportation tunneling and signaling systems. This led to destructive malware targeting the city’s water treatment plants.

JV 1.0 involved 25 organizations and 137 participants from six critical infrastructure sectors: financial services, emergency services, communications, healthcare, energy, and transportation systems. Developed with industry partner CITI, JV 1.0 examined interdependencies among critical infrastructure service providers in NYC. The ACI examined these interdependencies by assessing the performance of federal, state, and local governments, as well as private industry, in the event of a “Cyber Worst Day” scenario.

***
<sup>13</sup> Monken et al., *Cyber Mutual Assistance Workshop Report.*
{: .fs-2}
<sup>14</sup> Army Cyber Institute (ACI), *Jack Voltaic Executive Summary* (West Point, NY: United States Military Academy, 2016); and Joseph W. Pfeifer, “Preparing for Cyber Incidents with Physical Effects,” The *Cyber Defense Review* 3, no. 1 (2018): 26.
{: .fs-2}
***

The main objective of JV 1.0 was to identify a framework in which to rehearse a city’s coordinated responses to cyber incidents affecting multiple sectors. This exercise provided a venue in which participants could gain exposure, train players, and evaluate responses. The event produced the following findings:

- Cities still require their own ability to communicate up (to the state and federal levels) and across (within the city) to enable cyber preparation, prevention, and response.

- A municipality established cyber policy framework should inform and shape state and federal level polices.

- A municipality’s escalation processes should include identified industry partners and leverage local, state, and federal information sharing centers.

- Municipalities need to work through the process of an outage and determine whether it is cyber related.

- Explore, develop, and maintain public/private partnerships at the local, state, and federal levels to enable an integrated and coordinated incident response.

- Municipalities need to integrate public affairs/communications into their response plans.

#### 3.2.3. JV 2.0
A follow-up project to JV 1.0, JV 2.0 was a multi-sector, public-private cybersecurity research project that culminated in an exercise.<sup>15</sup> Occurring in July 2018, the 3-day event explored how a large city would respond to a simultaneous physical and cyberspace attack that could impact multiple critical infrastructure sectors. JV 2.0, which took place in Houston, explored the employment of the total Army force to defend the Nation in the face of a combined physical and cyberspace attack on a large U.S. port city as well as the cyber resiliency and readiness of Army-operated defense critical infrastructure to support military power projection and sustainment abroad from the port city. JV 2.0 centered on a hypothetical scenario in which a hurricane and cyberspace attack struck simultaneously in and around the Houston region. The event involved 44 organizations and 200 participants from eight critical infrastructure sectors.<sup>16</sup>

The intended outcome of JV 2.0 was to provide recommendations to U.S. Army Cyber Command (ARCYBER) on the development of strategies and procedures for defending large municipalities and critical infrastructure against cyberspace attacks and to develop Army cyber training objectives. Through JV 2.0, the ACI aimed to give state and regional civil officials a better understanding of how to leverage DoD and National Guard cyber capabilities to protect public and private critical infrastructure.

***
<sup>15</sup> Mitchell et al., *Jack Voltaic Critical Infrastructure.*
{: .fs-2}
<sup>16</sup> Benjamin Freed, “Why Local Governments Should Lead Multi-Jurisdiction Disaster Response,” StateScoop, April 23, 2019, https:// statescoop.com/why-local-governments-should-lead-multi-jurisdiction-disaster-response/.
{: .fs-2}
***

JV 2.0 enabled the establishment of public-private partnerships and a better understanding of the responses of private industry and government at multiple levels, facilitating the identification of gaps and the defense of key critical infrastructure cyber terrain.<sup>17</sup> With increases in the number of infrastructure sectors and Army stakeholders, JV 2.0 represented a more complex response environment than JV 1.0. The more complex set of responses built on the insights from JV 1.0 yet offered its own insights. Some of the lessons learned were:

- Political and civil agency leadership must view cyberspace as an operational domain involving adversaries who respond to contact, rather than viewing it in terms of static concepts of IT or cybersecurity architecture and policies. 

- Cities should revisit their network monitoring of all OT / supervisory control and data acquisition (SCADA) systems in each sector to ensure that only secure communications between production networks and the open Internet are allowed. 

- Though there are existing means for enabling cyber preparation, prevention, and responses, cities must have their own ability to communicate across (within the city), up (to the state and federal level and supporting sectors), and beyond (with commercially owned and operated critical infrastructure). 

- Cyber policy development at the city/county level is needed to inform and shape state and federal policies. 

- Cities and counties should engage in cyber exercises because they provide opportunities for local governments and private sector partners to experiment in a safe and trusted environment and collaboratively work through challenges, share best practices, and develop processes and procedures.

#### 3.2.4. JV 2.5
In summer 2019, the ACI held the JV 2.5 Cyber Workshop Series in the port cities of San Diego, Tacoma, San Francisco, Savannah, Charleston, Augusta, and Norfolk.<sup>18</sup> The objectives of the cyber workshop series were to: 

- Engage the owners of high-priority DoD critical infrastructure as well as municipality leaders on key relationships between commercial critical infrastructure and DoD critical missions; 

- Disseminate information and educate public and private entities on the lessons learned from JV 2.0; 

- Increase cyber awareness knowledge and provide information on cyber response option support; and 

- Prepare for the JV 3.0 exercise.

***
<sup>17</sup> Natasha Cohen, *Cyber Incident Response and Resiliency in Cities: How Partnerships Can Be a Force Multiplier* (Washington, DC: New America, updated February 21, 2019).
{: .fs-2}
<sup>18</sup> ACI, “Jack Voltaic 2.5 Cyber Workshop Series,” ACI (website), 2019, https://cyber.army.mil/Portals/3/Documents/JackVoltaic/Jack%20Voltaic%202_5%20InfoSheet_v4.pdf?ver=2019-08-20-153840-620.
{: .fs-2}
***

In support of these missions, AECOM and the ACI, in conjunction with the Department of Homeland Security (DHS) National Exercise Division, conducted a series of 1-day training workshops to share insights from JV 2.0 and discuss how similar efforts have the potential to strengthen the cyber resiliency of DoD missions. The workshops also helped to inform the scope of JV 3.0, which was still in its planning stages. Some of the key findings from the workshop series include: 

- Cyber intrusions are considered an IT, not an operational, problem. 

- The National Guard and the Reserves can serve as a very valuable DoD interface with local communities. 

- There is a dearth of information sharing and dialogue between communities and DoD installations, but communities where DoD and community leaders work together can move faster to take the right next steps. 

- At all levels, the operational planning community needs to emphasize and seamlessly integrate physical–cyber acknowledgment and response efforts that highlight IT- and OT-dependent systems. 

- National-level exercises do not provide information on the readiness level of local communities, where incidents are occurring with increasing frequency. 

- Partnerships, both public-private and public-public, are based on personal relationships in almost every location and need to be institutionalized.

Compounding observations from the JV research series that include more recent events, such as the JV 2.5 and JV 3.0 Legal and Policy Tabletop Exercise (TTX), include: 

- Crisis management and remediation is personality driven. 

- Individuals and organizations tend to lack experience with real cyber events and thus have difficulty visualizing second-, third-, and fourth-order effects; this inhibits a true understanding of interdependencies between organizations. 

- Municipalities and private entities tend to lack cyber policies that are complete, executable, resourced, and accessible, whether specific frameworks or as annexes to existing crisis management policies, and too often treat cyber incidents as information technology concerns. 

- Municipalities and organizations generally do not know what resources are available or who provides them during a cyber event; this result in hesitancy to declare a cyber incident.<sup>19</sup> 

- Define and plan a follow-on experiment to examine interdependencies among critical infrastructure sectors.

***
<sup>19</sup> Robin L. Fontes et al., “Jack Voltaic®: Bolstering Critical Infrastructure Resilience,” *The Cyber Defense Review* 5, no. 3 (2020): 50–53.
***


</div>

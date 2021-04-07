---
layout: default
title: § Cybersecurity in Elections - Models of Interagency Collaboration  
parent: Politics 
has_children: true
nav_order: 9810512 
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
This is the mobile-friendly web version of the [original article](https://www.idea.int/sites/default/files/publications/cybersecurity-in-elections-models-of-interagency-collaboration.pdf).

## IDEA INTERNATIONAL
{: .no_toc }
###  International Institute for Democracy and Electoral Assistance
{: .no_toc }
# Cybersecurity in Elections - Models of Interagency Collaboration 
{: .no_toc }

### Sam van der Staak and Peter Wolf 
{: .no_toc }

<iframe src="https://www.youtube.com/embed/K4MDleKPG2g" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
**Video:** Supporting democracy for 25 years. What's next?

### July 19, 2019
{: .no_toc }

© 2019 International Institute for Democracy and Electoral Assistance

This publication is independent of specific national or political interests. Views expressed in this publication do not necessarily represent the views of International IDEA, its Board or its Council members.

The electronic version of this publication is available under a Creative Commons AttributeNonCommercial-ShareAlike 3.0 (CC BY-NC-SA 3.0) licence. You are free to copy, distribute and transmit the publication as well as to remix and adapt it, provided it is only for non-commercial purposes, that you appropriately attribute the publication, and that you distribute it under an identical licence. For more information on this licence visit the Creative Commons website: .

International IDEA
Strömsborg
SE–103 34 Stockholm
Sweden
Telephone: +46 8 698 37 00
Email: info@idea.int
Website: <http://www.idea.int>

Design and layout: International IDEA
Cover image: ID 125793633 © Blackboard373 / Dreamstime.com
DOI: <https://doi.org/10.31752/idea.2019.23>

ISBN: 978-91-7671-255-9

Created with Booktype: <https://www.booktype.pro>

1. TOC
{:toc}

## Contents
- Preface
- Acknowledgements
- Abbreviations
- Definitions and scope of this document
- 1.Introduction
- 2.Cyberthreats throughout the electoral cycle
    - 2.1. Attacks targeting election-related technologies
    - 2.2. Vulnerabilities
    - 2.3. Disinformation targeting the perceived integrity of the electoral process
    - 2.4. Adversaries
    - 2.5. Mitigation measures
    - 2.6. The need for interagency collaboration
- 3.Models of interagency collaboration
    - 3.1. Number and type of agencies involved
    - 3.2. Dedicated forums and administrative bodies
    - 3.3. Cooperation between different levels of the EMB
    - 3.4. Cooperation with non-state agencies
- 4.Operationalizing interagency collaboration
    - 4.1. Focus areas
    - 4.2. Setting up and facilitating interagency collaboration
- 5.Conclusions and recommendations
- Annex A: Case studies
    - Australia
    - Austria
    - Bulgaria
    - Canada
    - Denmark
    - Estonia
    - European Union
    - Finland
    - Georgia
    - Latvia
    - Mexico
    - Moldova
    - The Netherlands
    - Norway
    - Romania
    - South Africa
    - Sweden
    - Ukraine
    - United Kingdom
    - United States of America
- References and further reading
- About the authors
- About International IDEA

## Preface

Information and communication technologies are increasingly prevalent in electoral management and democratic processes. These technologies offer numerous new opportunities, but also new threats. Cybersecurity is currently one of the greatest electoral challenges, even for countries without any form of electronic voting. It involves a broad range of actors, including electoral management bodies, cybersecurity expert bodies and security agencies. Many countries have found that interagency collaboration is essential for defending elections against digital threats. In recent years significant advances have been made in organizing such collaboration at the domestic and international levels.

This guide tracks how countries are making progress on improving cybersecurity in elections. Based on an extensive collection of 20 case studies from all over the world, it provides lessons for those wanting to strengthen their defences against cyberattacks.

As digital developments affect more of our societies every day, all countries will need to invest in protecting their elections from cyberthreats. We hope this guide will succeed in sharing these cybersecurity experiences with audiences far beyond the countries that had an opportunity to participate in our activities.

*International IDEA*

## Acknowledgements
This Guide was developed in cooperation between the International IDEA’s Regional Europe Programme and Global Programme.

Invaluable input, case study interviews and presentations were provided by individuals at a range of institutions, including the Australian Electoral Commission, the Austrian Federal Ministry of Interior, the Central Election Commission of the Republic of Bulgaria, Election Canada, the Ministry of Economic Affairs and the Interior in Denmark, the State Electoral Office of Estonia, the Cybersecurity Branch of the Estonian Information System Authority, the Finnish Legal Register Centre, the Georgian Central Election Commission, the State Chancellery of Latvia, the Central Election Commission of Latvia, the Central Election Commission of Lithuania, the Instituto Nacional Electoral of Mexico, the Central Electoral Commission of the Republic of Moldova, the Dutch Electoral Council, the Permanent Election Authority of Romania, the Independent Election Commission of South Africa, the Swedish Election Authority and the Swedish Civil Contingencies Agency, the Security Service of Ukraine, the UK Electoral Commission, the UK National Cybersecurity Centre and the US Election Assistance Commission.

The Guide benefited from valuable input and suggestions from colleagues at International IDEA, including Therese Pearce Laanela and Adina Trunk, as well as diligent editing and note taking by Alyssa Bittner-Gibbs, Oliver Joseph, Dominika Michalak and Maryam Safi. We also extend our appreciation to Lisa Hagman and Lucy Smith for overseeing the production of this Guide.

## Abbreviations
**CEC** Central Election Commission

**CERT** Computer Emergency Response Team

**CSE** Communications Security Establishment

**DDoS** Distributed Denial of service

**DHS** Department of Homeland Security

**DoS** Denial of service

**EAC** Electoral Assistance Commission

**EMB** Electoral management body

**ES** Election Section

**ICT** Information and communication technology

**IEC** Independent Electoral Commission

**INE** National Electoral Institute of Mexico

**MoEAI** Ministry of Economic Affairs and the Interior

**MoJ** Ministry of Justice

**NCSC** National Cybersecurity Centre

**NGO** Non-governmental organization

**PEA** Permanent Electoral Authority

**PEC** Precinct Election Commission

**SISA** State Information System Authority

**SSSCIP** State Service of Special Communications and Information Protection of Ukraine

## Definitions and scope of this document
*Cyber-risks* refer to any risk of financial loss, disruption or damage to the reputation of an organization due to a failure of its information technology systems. Here the term also includes risks stemming from disinformation about electoral administration and electoral technology that can occur even in the absence of system failures.

*Cybersecurity *relates to protecting Internet-connected systems, networks, software and data from unauthorized access or exploitation. It is also used here to include the security of offline election technologies and protecting the integrity of the electoral process from disinformation and influence operations.

*Cyberthreats* in elections include threats to all possible technology based on hostile and/or illegal acts designed to undermine the integrity of the electoral process.

*Interagency collaboration* is used here to indicate collaboration designed to prevent and mitigate cyber-risks and respond to cyber-related incidents in elections. Such collaboration is not necessarily limited to government agencies; it also includes a broad range of actors, including EMBs, media and social media providers, political parties, electoral candidates, civil society and other electoral stakeholders, as well as private sector actors including election technology providers and consultants.

*Vulnerabilities* are weaknesses in the electoral process that make it prone to successful or alleged attacks. Such weaknesses can include the technology (devices, software, networks) itself as well as inadequate procedures and human factors such as poorly trained staff.

The scope of this publication focuses on cyber-risks and threats in electoral processes that fall within the responsibility of an EMB. This includes a broad range of possible attacks against the confidentiality, integrity and availability of election-related data and technology. For social media and other forms of online publications, this includes spreading disinformation about the electoral process.
</div>

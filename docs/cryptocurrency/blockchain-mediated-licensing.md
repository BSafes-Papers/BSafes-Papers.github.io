---
layout: default
title: § Blockchain-mediated Licensing - Legal Engineering for Artist Empowerment  
parent: Cryptocurrency 
has_children: true
nav_order: 9800523 
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

.youtube-container {
    position: relative;
    width: 100%;
    height: 0;
    padding-bottom: 56.25%;
}
.youtube-video {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
}

</style>

<div class="dont-break-out" markdown="1">
This is the mobile-friendly web version of the [original article](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3625317).

![Blockchain-mediated Licensing](https://statics.bsafes.com/images/papers/blockchain-mediated-licensing.png)

# Blockchain-mediated Licensing 
{: .no_toc }
## Legal Engineering for Artist Empowerment
{: .no_toc }

## Contributors: Charles Adjovu; Ewa Fabian
{: .no_toc }

### LEDGERBACK.COOP
1. TOC
{:toc}

## Contents

- Abstract

- Introduction

- I) Background Research
    - 1) Literature Review 2
        - 1.1 Scoping Review 
        - 1.2 Research Questions 
        - 1.3 Report Structure 
        - 1.4 Research Methodology 
            - 1.4.1 Search 
            - 1.4.2 Screening
            - 1.4.3 Review Results
        - 1.5 Music Business Perspective 
            - 1.5.1 Blockchain Impacts & Policy Concerns 
            - 1.5.2 Blockchain Supply Chain
            - 1.5.3 Blockchain-based Music Platforms 
        - 1.6 Legal Perspective 
            - 1.6.1 Electronic Signatures & Evidence
            - 1.6.2 Contract Law 
            - 1.6.3 Copyright Law 
        - 1.7 Automation Perspective 
            - 1.7.1 Smart Contracts 
            - 1.7.2 Metadata 
            - 1.7.3 Semantic Web 
            - 1.7.4 Ricardian Contracts 
            - 1.7.5 Online Dispute Resolution 
            - 1.7.6 Legal Engineering 
        - 1.8 Value Web Perspective

    - 2) Music Industry Supply Chain and Work Registration Standards 

    - 3) Legal Frameworks Primer 

        - 3.1 International Copyright Treaties
        - 3.2 United States of America (USA) 
            - 3.2.1 Copyright Law 
            - 3.2.2 Contract Law 
            - 3.2.3 Electronic Records & Signatures 
        - 3.3 European Union (EU) 
            - 3.3.1 Digital Single Market 
            - 3.3.2 Copyright 
            - 3.3.3 Electronic Identication
            - 3.3.4 General Data Protection Regulation (GDPR) 
        - 3.4 Alternative Dispute Resolution

    - 4)  Music Licensing Primer 
        - 4.1 Music License Typology 
        - 4.2 Licensing Approaches
            - 4.2.1 Blanket Licensing Model
            - 4.2.2 Compulsory Licensing Model
            - 4.2.3 Creative Commons Licensing Model
        - 4.3 Territorially-restrictive Licensing
        - 4.4 Licensing Costs and Issues

    - 5) Technology Primer
        - 5.1 Blockchain
        - 5.2 Smart Contracts
        - 5.3 InterPlantery File System (IPFS)
        - 5.4 Application Programming Interface (API) and Data Oracles
        - 5.5 Decentralized Applications (DApps) 
        - 5.6 Digital Assets 
        - 5.7 Non-fungible Tokens (NFTs)
        - 5.8 Linked Data
        - 5.9 Ricardian Contracts

- II) Ricardian Contract 

    - 6) Motivation 

    - 7) Decentralized Media Platforms
        - 7.1 Musicoin
        - 7.2 Resonate
        - 7.3 Choon
        - 7.4 Creativechain
        - 7.5 LBRY
        - 7.6 Ujo Music
        - 7.7 The Wicked Costs of Decentralized Media Platforms
        - 7.8 The Need for Greater Licensing Options

    - 8) Methods
        - 8.1 Practical Tokenized Drafting (PTD)
            - 8.1.1 Core Principles
            - 8.1.2 Core Design Practices
        - 8.2 Automating Legal Prose
        - 8.3 Automated Music License Methods

    - 9) Discussion
        - 9.1 Standard Form Design
        - 9.2 Research Limitations
        - 9.3 Future Research Areas

- Conclusion

- References

- Appendix

## About The Emerging Technologies Research Group
The Greyscail Blockchain Review is housed in the Emerging Technologies research group at the Ledgerback Digital Commons Research Cooperative (LDCRC). The research group's mission is to increase innovation di usion of Web3 and other emerging technologies that empower individuals and peer-to-peer interactions so that they become commonplace in our society. This research report is one activity towards achieving that vision. As the Emerging Technologies research group aims to be platform-agnostic, open and inclusive, we have licensed this report under an open access license. Additionally, we aim to make this report available on multiple platforms, regardless of the platform's underlying technology so that even those who are not yet part of the Web3 ecosystem can enjoy this report.

## Acknowledgements
We would like to thank everyone who helped us in developing this research report. Speci cally, we would like to thank Coopérative Kleros, Veri Media, and our music composer interviewee. 

We would like to thank Coopérative Kleros for providing input on blockchain-based ADR and escrow, and on addressing copyright issues in the music industry. 

We would like to thank our music composer interviewee <sup>1</sup> for providing input on the issues and concerns faced by music composers and how such concerns could be addressed. 

We would like to thank Veri  Media for providing input on how a musician can register with Veri  Media to receive a metadata bundle for their musical work. 

Charles Adjovu would like to thank Ewa Fabian for inspiring him to continue his research at Ledgerback Digital Commons Research Cooperative (LDCRC) after seeing her blog post reviewing LDCRC's  rst report on this topic, reinvigorating his desire to work on this research report, and to dive deeper into blockchain applications for the music and legal industries.

***
<sup>1</sup>Name excluded to preserve interviewee privacy
{: .fs-2}
***

## Disclaimers

Contact: Charles Adjovu, ledgerback@gmail.com.

Copyright © 2020 Charles Adjovu and Ewa Fabian. Ledgerback Digital Commons Research Cooperative © 2020 Greyscail Blockchain Review. 

Any dispute related to the use of this work that cannot be settled amicably shall be submitted to arbitration pursuant to the UNCITRAL rules. 

The opinions expressed in this publication are those of the authors and do not necessarily re ect the views of Ledgerback Digital Commons Research Cooperative (LDCRC), its Board of Directors, its Members, or its affiliates. 

The mention of any trademark, copyright, name, logo, or other protected intellectual property, or proprietary property is solely for normative purposes. All rights are reserved to their respective owners. 

Nothing contained herein should be construed as, or is intended to be,  nancial or legal advice. This research report is intended solely for research purposes. 

You agree and acknowledge that no attorney-client relationship of any kind shall be created from reading this research report or from any future uses of this research report. 

While the authors aim to provide up-to-date and accurate information, the authors make no guarantees about the recentness or accuracy of the information contained in this report.

## Publishing Information

### Publishing

**Publisher**
Ledgerback Digital Commons Research Cooperative   
Emerging Technologies Research Group  
Las Vegas, Nevada, USA

**Design & Layout**
Ledgerback Digital Commons Research Cooperative

**Contact**
Ledgerback Digital Commons Research Cooperative  
Email: ledgerback@gmail.com

**Excluded Sections**
If you would like access to the sections excluded from this version of the final print, please send an email to ledgerback@gmail.com with the subject line: "Access to Excluded Sections of the Blockchain-mediated Licensing Report".

Excluded sections:

- List of Cases

- List of Statutes

**Suggested Citation**
Charles Adjovu and Ewa Fabian, Blockchain-mediated Licensing: Legal Engineering for Artist Empowerment 1 - 99, Greyscail Blockchain Review (GreyscailØLDCRC 2020).

### Author Information

**Affiliations**
*Ledgerback Digital Commons Research Cooperative, Las Vegas, Nevada, USA* Charles Adjovu

*Independent Researcher*
Ewa Fabian

**Identifiers**
*ORCID:*
Charles Adjovu: 0000-0001-6206-9546

**Corresponding Author**
Correspondence to Charles Adjovu.

### Ethics Declarations
**Funding Statement**
This report received no external funding

**Conflicts of Interests**
The authors declare no conicts of interest

### Rights and Permissions
**Open Access**
This report is licensed under a Creative Commons Attribution 4.0 International Public License (CC-BY 4.0) license, which permits use, sharing, adaptation, distribution and reproduction in any medium or format, as long as you give appropriate credit to the original author(s) and the source, provide a link to the Creative Commons license, and indicate if changes were made. 

If material is not included in the report's Creative Commons license and your intended use is not permitted by statutory regulation or exceeds the permitted use, you will need to obtain permission directly from the intellectual property holder. To view a copy of this license, visit http://creativecommons.org/licenses/by/4.0/. 

The use of the Ledgerback Digital Commons Research Cooperative ("LDCRC") name or logo for any purpose other than for attribution shall be subject to a separate written license agreement between LDCRC and the user and is not authorized as part of this CC-BY 4.0 license.

### CRediT Authorship & Contribution Statement
Charles Adjovu: Conceptualization, Writing - original draft, Writing - review & editing, Software, Project administration, Data curation, Methodology.

Ewa Fabian: Conceptualization, Writing - original draft.

Charles Adjovu and Ewa Fabian jointly contributed to the International Copyright section of the Legal Frameworks Primer. Ewa Fabian contributed the European Union (EU) section of the Legal Frameworks Primer and the Views on Smart Contracts subsection of the Automation Perspective. Charles Adjovu contributed all other parts of this report.

### Release Delay and Quality of the Literature Review
Technical issues prevented us from completing the editing process for this version of the report, in particular for Part I, by the expected release date. We apologize for any ambiguity, awkward phrasing or inaccuracies that may be appear in Part I. Our need to rectify our failure to meet the expected release date led us to release this version of the report, even with some errors, because we wanted to make the report (at least an acceptable version of the report) available to the public as soon as possible. For the above reasons, our Literature Review in Part I is more akin to an annotated bibliography than a traditional literature review. We apologize for the lack of critical analysis and integration of our sources in the Literature Review and for its extensive length. Lastly, we apologize for any inconvenience our delay in releasing this version of the report may have caused.

### Alternative Titles
A list of alternative titles for this report:
- Computer-mediated Licensing: Legal Engineering for Artist Empowerment;
- Computer-aided Licensing: Legal Engineering for Artist Empowerment;
- Techno-licensing: Legal Engineering for Artist Empowerment;
- Technology-mediated Licensing: Legal Engineering for Artist Empowerment;
- Internet-mediated Licensing: Legal Engineering for Artist Empowerment;
- Web-mediated Licensing: Legal Engineering for Artist Empowerment;
- Blockchain-augmented Licensing: Legal Engineering for Artist Empowerment;
- Network-mediated Licensing: Legal Engineering for Artist Empowerment;
- Computer-assisted Licensing: Legal Engineering for Artist Empowerment; and
- Can't Stop The Music Licensing: Legal Engineering for Artist Empowerment;
- Ricardian Contracts for Music Licensing: Legal Engineering for Artist Empowerment;
- Web3-mediated Licensing: Legal Engineering for Artist Empowerment; and
- Global Licensing with Web3 Technologies: Legal Engineering for Artist Empowerment.

You may use one of the alternative titles of this report if it better suits your needs.

### Peer Review Status
This report has not been peer reviewed. We do invite peer review of this report and any such peer review may be sent to the contact or corresponding author for this report.

### Audience
This report is intended for multiple audiences, including legal practitioners<sup>2</sup> wondering how Web3 technologies will a ect legal drafting, researchers who want to understand how blockchain technology interacts with legal frameworks, music industry stakeholders who need deeper insights on blockchain's impact on the industry, students at the university level whose interests or focus is on blockchain, law, or music, and participants in the Web3 ecosystem who are interested in this area or intend to disrupt the music industry. Given the audience diversity, we included a reading guide to help readers navigate this report and focus on the areas important to them.

***
<sup>2</sup>Legal practitioner and legal professional are used synonymously throughout this report.
{: .fs-2}
***

## Reading Guide
This reading guide, further described below, is meant to help readers navigate through this report in an easy-to-read manner. 

You may read this report in non-sequential order because each chapter is independent of the other chapters. Though, we do recommend reading each chapter to have a greater understanding of the intersection of music complexity and Web3 technologies. 

If you have prior knowledge on any of the perspectives in the Background Research section, we recommend moving on to the other perspectives. 

If you are interested in the research literature at the intersection of music complexity and Web3 technologies, please refer to the Background Research section. 

If you are interested in a brief introduction to digital music supply chain and work registrations standards, please refer to Music Industry Supply Chain and Work Registration Standards. 

If you are interested in the legal frameworks, please refer to the Legal Frameworks Primer in Part I. 

If you are interested in music licensing speci cally, please refer to the Music Licensing Primer in Part I. 

If you are interested in the relevant technologies, please refer to the Technology Primer in Part I.

If you are interested in our development of the Tokenized Music License (TML), a Ricardian Contract standard form for music licensing that interacts with Web3 technologies (RC-Web3 Template), please refer to Part II. 

For an essential reading of this report, we recommend reading the Literature Review in Part I and the Methods and Discussion in Part II.

#### List of Abbreviations and Acronyms

**ADR** Alternative Dispute Resolution

**AMP** Allocation for Music Producers Act

**API** Application Programming Interface

**ASCAP** American Society for Composers, Authors and Publishers

**AT** Audit Template

**BY** Attribution

**CBD** Crea-based Dollar

**CC** Creative Commons

**ccREL** Creative Commons Rights Expression Language

**CC BY** Attribution

**CC BY-SA** Attribution-ShareAlike

**CC BY-ND** Attribution NoDerivs

**CC BY-NC** Attribution NonCommercial

**CC BY-NC-ND** Attribution-NonCommercial-NoDerivs

**CC BY-NC-SA** Attribution-NonCommercial-ShareAlike

**CGY** Crea Energy

**CID** Content Identifier

**CISAC** International Confederation of Societies of Authors and Composers

**CLASSICS** Compensating Legacy Artists for their Songs, Service, & Important Contributions to Society

**CMO** Collective Management Organization

**COALA-IP** Coalition of Automated Legal Application - Intellectual Property

**CWR** Common Works Registration

**DAO** Decentralized/Distributed Autonomous Organization

**DApp** Decentralized Application

**DC** Draft Commentary

**DDoS** Distributed Denial of Service

**DeFi** Decentralized Finance

**DID** Decentralzied Identifiers

**DHT** Distributed Hash Table

**DLP** Drafting Legal Prose

**DLT** Distributed Ledger Technology

**DMCA** Digital Millennium Copyright Act

**DOJ** Department of Justice

**DPoS** Delegated Proof-of-Stake

**DRM** Digital Rights Management

**DSP** Digital Music Service Providers

**ERC** Ethereum Request for Comments

**E-sign** Electronic Records in Global and National Commerce Act

**EM** Entity Model

**ETH** Ether

**EU** European Union

**EUIPO** European Union Intellectual Property Office

**EVM** Ethereum Virtual Machine

**FAQ** Frequently Asked Questions

**GDPR** General Data Protection Regulation

**GUI** Graphical User Interface

**HTTP** Hypertext Transfer Protocol

**ILP** InterLedger Protocol

**IP** Intellectual Property

**IPFS** InterPlanetary File System

**IPLD** InterPlanetary Linked Data

**ISNI** International Standard Name Identier

**ISP** Internet Service Provider

**ISRC** International Standard Recording Code

**ISWC** International Standard Musical Work Code

**IT** Information Technology

**JSON** JavaScript Object Notation

**JSON-LD** JavaScript Object Notation-Linked Data

**LBC** LBRY Credits

**LCC** Linked Content Coalition

**LD** Linked Data

**MAR** Minimum Automation Requirements

**MCF** Musicoin Foundation

**MIT** Massachusetts Institute of Technology

**MLC** Mechanical Licensing Collective

**MLR** Minimum Legal Requirements

**MMA** Music Modernization Act

**MME** Music Moves Europe

**MRO** Mechanical Rights Organization

**MTR** Minimum Technical Requirements

**MVD** Minimum Viable Data

**NC** NonCommercial

**ND** NoDerivs

**NFT** Non-fungible Token

**NOI** Notice of Intention to Obtain a Compulsory License

**OMI** Open Music Initiative

**PKI** Public-Key Infrastructure

**PNK** Pinakion

**PoC** Proof-of-Concept

**PoS** Proof-of-Stake

**PoW** Proof-of-Work

**PPP** Pay-Per-Play

**PRO** Performing Rights Organization

**PSC** Programming Software Components

**PTD** Practical Tokenized Drafting

**P2P** Peer-to-Peer

**P&S** Prose and Software

**RC** Ricardian Contract

**RDF** Resource Description Framework

**REL** Rights Expression Language

**RMI** Rights Management Information

**RRM** Rights Reference Model

**RL** Release License

**SA** ShareAlike

**SACEM** Society of Authors, Composers and Publishers of Music

**SSID** Self-Sovereign Identity

**ToS** Terms of Service

**TPS** Transactions-per-second

**TRIPS** Trade-Related Aspects of Intellectual Property Rights

**TML** Tokenized Music License

**TPM** Technological Protection Measures

**TT** Test Template

**UBI** Universal Basic Income

**UCC** Universal Copyright Convention

**UCC Art. 2** Uniform Commercial Code Article 2

**UETA** Uniform Electronic Transactions Act

**UNCITRAL** United Nations Commission on International Trade Law

**URI** Uniform Resource Identifier

**URL** Uniform Resource Locator

**US/USA** United States of America

**USD** United States of America Dollar

**USPTO** United States Patent and Trademark Oce

**VARA** Visual Artists Rights Act

**WCT** World Intellectual Property Organization Copyright Treaty

**WIPO** World Intellectual Property Organization

**WTO** World Trade Organization

**W3C** WorldWideWeb Consortium

**XML** eXtensible Markup Language

**ZKP** Zero-Knowledge Proof

## Abstract
Licensing is one of the essential means of exploiting the monetary value of a musical work, and yet it is an area fraught with many issues and transactional costs which make it a difficult process for individuals and organizations. Many issues in music licensing arise from the legal complexity (e.g., national and international copyright law), business complexity (authentication, tracking, accounting, etc.), value web complexity (transparency of relationships among stakeholders), and technical complexity (e.g., establishing a global repertoire database for music, sufficient metadata standards) of working with music. Then, in addition to these issues, there are specific transactional costs (identification, negotiation, monitoring, and enforcement) associated with the licensing process. To mitigate the complexity and transactional costs associated with music and the licensing process, researchers and technologists have been investigating how new technologies and design models from the Web3 space, such as blockchain, linked data and Ricardian Contracts, can automate processes to reduce complexity, speed up payments, improve tracking, and provide other benefits in the music industry. In our report, we make our own attempt to reduce the complexity and transactional costs in the licensing process by developing an automated music license. In doing so, we  first conducted a literature review synthesizing the intersection of music complexity and Web<sup>3</sup> technologies to provide background and context to automating music licensing. Then we developed the Practical Tokenized Drafting (PTD) method, a set of core principles and practices for drafting Ricardian Contracts that interact with Web3 technologies (RC-Web3 Templates), and the Tokenized Music License (TML), an RC-Web3 Template standard form for music licensing on the OpenLaw platform. Both the PTD and TML can be adapted to meet the needs of music industry stakeholders and provide guidance to legal practitioners in drafting RC-Web3 Templates.
</div>

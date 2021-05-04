---
layout: default
title: 8) Methods 
parent: § Blockchain-mediated Licensing - Legal Engineering for Artist Empowerment  
grand_parent: Cryptocurrency 
nav_order: 800 
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
1. TOC
{:toc}

## 8 Methods

### 8.1 Practical Tokenized Drafting (PTD)
In developing our automated music license, we developed the Practical Tokenized Drafting (PTD) method, a set of core principles and design practices for drafting RCs that interact with Web3 technologies (with an emphasis on blockchain and smart contracts) (hereafter "RC-Web3 Templates"). Our PTD method is an outgrowth of legal engineering and automated transactions. PTD is an outgrowth of legal engineering because we are tokenizing a simple system, here being the copyright in musical works, with the aid of RCs and Web3 technologies.968 PTD is an outgrowth of automated transactions because the method explicitly describes practices for utilizing machines to execute and store some dimension of an exchange of value, and this is actualized through the Tokenized Music License (TML).<sup>969</sup> Our PTD method was derived from Veri  Media's Minimum Viable Data (MVD) standard, our Literature Review, and our interviews with a music composer and Coopérative Kleros.

In PTD, we approach drafting with three (3) core principles and ten (10) core design practices in mind from creation to testing to finally release, from the viewpoint of a legal practitioner (used synonymously with drafter) working individually or in partnership with a software engineer(s) (i.e., a programmer).

The three core principles of PTD are:

1. Stay On-chain<sup>970</sup>;

1. Seek Minimalism; and

1. Jurisdiction Agnostic.

The ten core design practices of PTD are:

1. Minimum Legal Requirements;

1. Minimum Technical Requirements;

1. Drafting Legal Prose;

1. Minimum Automation Requirements;

1. Programming Software Components;

1. Prose & Software;

1. Draft Commentary;

1. Test Template;

1. Audit Template; and

1. Release Template.

#### 8.1.1 Core Principles

**Stay On-chain**
The  first principle, Stay On-chain, is to guide the legal practitioner to always approach PTD with an on-chain  rst mindset. In other words, the legal practitioner should always be looking for ways to keep the interactions between the parties, and the execution and enforcement of the RC-Web3 Template, on the blockchain, online, or handled by another Web3 technology. By keeping matters on-chain, the legal practitioner can reduce the variability that may arise because of different types of users, territories, and legal systems.

***
<sup>968</sup>Supra Section 1.7.6.
{: fs-2}
<sup>969</sup>Supra Section 1.7.1.
{: fs-2}
<sup>970</sup>On-chain is a term often used to signify that something is stored and created on, or interacted with, wholly or partially on a blockchain.
{: fs-2}
***

**Seek Minimalism**
The second principle, Seek Minimalism, is directly inspired by Verifi  Media's MVD standard. As applied to PTD, the legal practitioner should try to simplify the agreement (i.e., reduce complexity) to its most essential parts (this will also help in figuring out the MAR practice) that can be specifically handled reasonably well with Web3 technology by a RC-Web3 Template.

**Jurisdiction Agnostic**
The third principle, Jurisdiction Agnostic, is to guide the legal practitioner to avoid using multiple jurisdictions or try to find a common ground on jurisdiction between the parties because the parties in a RC-Web3 Template context are likely to span multiple jurisdictions. By keeping the jurisdiction limited to one or few, it will be easier for the parties to know what to expect when utilizing a RC-Web3 Template and reduce the chances of unexpected legal occurrences arising from the different legal frameworks of jurisdictions. A good way to apply this principle is to look for jurisdictions that have adopted international treaties and agreements applicable to the subject matter of the agreement.

#### 8.1.2 Core Design Practices

**Minimum Legal Requirements**
The Minimum Legal Requirements (MLR) practice requires the drafter to consider the legal frameworks that prescribe the boundaries and minimum requirements of the legal subject matter of the agreement. For any RCWeb3 Templates, the drafter will need to evaluate the following laws, rules and regulations applicable in their jurisdiction(s):

- Electronic Signatures;

- Electronic Transactions;

- Contracts<sup>971</sup>;

- Evidence;

- Alternative Dispute Resolution;

- International Treaties;

- Tax Liability;

- Conflict of Laws;

- Data Privacy; and

- Web3-specific laws and regulations.<sup>972</sup>

##### Minimum Technical Requirements
The Minimum Technical Requirements (MTR) practice requires the drafter to consider the technical frameworks for the desired Web3 infrastructure and best practices for developing Web3-interactive programmable software components. For example, since the OpenLaw platform is on Ethereum, the drafter will need to consider the following:

***
<sup>971</sup>Especially contractual remedies.
{: fs-2}
<sup>972</sup>Additionally, a drafter may need to consider securities laws and trade laws.
{: fs-2}
***

- programming frameworks and best practices for deploying a smart contract on the Ethereum blockchain<sup>973</sup>; and

- how transactions on OpenLaw are conducted and stored on the Ethereum blockchain.

For an additional example, if the drafter wants to deploy an ERC-20 token to the Ethereum blockchain, the drafter should examine the ERC-20 token standard and good practices associated with ERC-20 tokens.

##### Drafting Legal Prose

The Drafting Legal Prose (DLP) practice requires the drafter to draft the legal prose of the RC-Web3 Template in accordance with the MLR practice and the purpose of the legal document.

##### Minimum Automation Requirements
The Minimum Automation Requirements (MAR) practice requires the drafter to consider which parts of the legal prose are ripe for automation. Generally, the objective and computable provisions can be automated (e.g., payments, dates and times), while the subjective or di cult to compute provisions should be left as legal prose. Additionally, any existing assets or rights are generally tokenizable.

##### Programming Software Components
The Programming Software Components (PSC) practice requires the drafter to program or cause to program, if not already programmed, the software components of the RC-Web3 Template (generally in accordance with the MTR practice). Additionally, the drafter needs to consider if they can directly embed the legal prose into the metadata of any  le containing a digital representation of the agreement's subject matter.

##### Prose & Software
The Prose and Software (P&S) practice requires the drafter to combine the legal prose, considerations for automation, and software components to produce one complete draft of the RC-We3 Template.

##### Draft Commentary
The Draft Commentary (DC) practice requires the drafter to draft commentary explaining to the relevant parties (licensor, licensee, drafters, etc.) the provisions of the RC-Web3 Template, the legal and technical contours of the RC-Web3 Template, and any disclaimers and licenses. Generally, this practice is akin to a cover letter explaining the agreement to a client.

##### Test Template
The Test Template (TT) practice requires the drafter to test the RC-Web3 Template on the Web3 infrastructure. For example, if the RC-Web3 Template is developed on the OpenLaw platform on the Ethereum blockchain, the drafter should execute the RC-Web3 Template on one of the Ethereum blockchain test networks, such as the Rinkeby network, or on a private Ethereum network.

##### Audit Template
The Audit Template (AT) practice requires the drafter to have a third-party audit (public or private) of the RC-Web3 Template's software components for security and optimization purposes.

***
<sup>973</sup>However, if the drafter is working with a software engineer well versed in Web3, then these considerations can be left with the software engineer
{: fs-2}
***

**Release Template**
The Release Template (RT) practice requires the drafter to release the RC-Web3 Template to the parties involved, or make available to the public, in an easily accessible and editable manner, such as a template on the OpenLaw platform. Additionally, if the RC-Web3 Template is made available to the public, the drafter should also include any copyright distribution licenses associated with the template, any preferred audiences, and the commentary for the RC-Web3 Template.

### 8.2 Automating Legal Prose
Automating legal prose raises serious issues concerning how to translate subjective terms in a legal document into objective programmable software.<sup>974</sup> An additional concern is also implied covenants in contracts, which are included even if the parties did not consider them. This is often the case for a duty of good faith and fair dealing.<sup>975</sup> Generally, terms that are easily computable (i.e., quantitative or tending to be quantitative) are the easiest to translate into programmable software (the programmable software we are most concerned with are smart contracts and we shall refer to smart contracts for the rest of this section), while terms that are subjective, indeterminable at the time of contracting, or ambiguous, are the hardest to translate into a smart contract.<sup>976</sup> Our perception of the di culty of translating legal prose, speci cally provisions in a copyright license, into smart contracts is described in the table below.

***
<sup>974</sup>Giancaspro, "Is a 'smart contract' really a smart idea? Insights from a legal perspective".
{: fs-2}
<sup>975</sup>Ibid.
{: fs-2}
<sup>976</sup>Giancaspro, "Is a 'smart contract' really a smart idea? Insights from a legal perspective".
{: fs-2}
***

Given some of the headaches of translating prose to software, we believe a middle ground approach such as a contract management platform that offers functionality with blockchain and other Web3 technologies (e.g., OpenLaw) would be the one of the best approaches for increasing adoption of Web3 technologies among legal professionals and music industry stakeholders.<sup>978</sup> Additionally, if the contract management platform allows the contracts made on the platform to integrate with DApps (built with smart contracts), then it becomes easier for musicians, other music industry stakeholders, and smart contract developers to build DApps using contracts that are legally-compliant while achieving transaction cost savings<sup>979</sup>

### 8.3 Automated Music License Methods
The OpenLaw platform, as discussed in Part I, is a Ricardian Contract (RC) development and hosting platform that interacts with the Ethereum blockchain and associated ecosystem.<sup>980</sup> OpenLaw provides a public repository for storing and extending RC-Web3 Templates, and has its own markup language for writing RC-Web3 Templates.<sup>981</sup> On OpenLaw, a record of all signed and executed RC-Web3 Templates is stored on the Ethereum blockchain, excluding the rich text (the legal prose, user-de ned variables and options, and party identification other than Ethereum public addresses drafted in the markup language) of the RC-Web3 Template.<sup>982</sup> This record includes all the required information for a transaction stored on the Ethereum blockchain, including the:

- public addresses (i.e., the proof that the parties exchanged cryptographic signatures) of the parties,

- timestamp of the transaction,

- Gas fees and Gas limit, and

- creation, interaction and/or execution of any smart contract functions (e.g., creating tokens, transferring tokens)<sup>983</sup>

We utilized OpenLaw to develop our automated music license standard form, aptly named the Tokenized Music License<sup>984</sup>, an RC-Web3 Template standard form for music licensing in a Web3 technologies context. Additionally, we created a form and  ow for the TML to guide users of the TML through the contracting process. The TML form and  ow is designed to guide users through the contracting process by first providing contact information, then filling out the particulars of the TML, and  finally ending with signatures.

Before using the OpenLaw platform, we read through the OpenLaw Docs to understand how:

- to design a template,

- to design a form and low, and

- OpenLaw RCs can interact with the Ethereum blockchain (e.g., cryptographically signing transactions and recording transactions on the blockchain) and associated ecosystem (e.g., DApps and data oracles)<sup>985</sup>

We heavily referenced the First Draft, Sign & Store, Forms & Flows, and Token Forge pages.<sup>986</sup> From the PTD method, we relied on the MLR, MTR, MAR, DLP and P&S core design practices. We determined our MLR,

***
<sup>978</sup>Finck and Moscon, Copyright Law on Blockchains: Between New Forms of Rights Administration and Digital Rights Management 2.0.
{: fs-2}
<sup>979</sup>Finck and Moscon, Copyright Law on Blockchains: Between New Forms of Rights Administration and Digital Rights Management 2.0; Bodó, Gervais, and Quintais, Blockchain and smart contracts.
{: fs-2}
<sup>980</sup>*Overview | OpenLaw Docs;* Finck and Moscon, Copyright Law on Blockchains: Between New Forms of Rights Administration and Digital Rights Management 2.0.
{: fs-2}
<sup>981</sup>*Overview | OpenLaw Docs*.
{: fs-2}
<sup>982</sup>Ibid.
{: fs-2}
<sup>983</sup>Ibid.
{: fs-2}
<sup>984</sup>The Tokenized Music License discussed in this report is Version 0.5 (V0.5), and a draft of V0.5 is included as an appendix to this report
{: fs-2}
<sup>985</sup>*Overview | OpenLaw Docs.*
{: fs-2}
<sup>986</sup>Ibid.
{: fs-2}
***

MTR, MAR from the Literature Review in Part 1.<sup>987</sup>For P&S considerations, we referred to COALA-IP's Licensing Protocol documentation and OpenLaw's documentation.<sup>988</sup> For DLP, we relied on our previous knowledge of intellectual property licensing and referred to two licenses:

1. ASCAP's Music-in-business Blanket License; and

1. Kadion Henry's Music License Agreement from Docracy. 

<sup>989</sup> Lastly, we relied on two interviews, one with a music composer and the other with the Kleros team, to aid in tailoring our TML for our intended circumstances.

***
<sup>987</sup>Supra Section 1.
{: fs-2}
<sup>988</sup>Supra Section 1.
{: fs-2}
<sup>989</sup>Kadion Henry. *Music License Agreement.* url: https : / / www . docracy . com / 6931 / music - license - agreement (visited on 12/10/2019); *ASCAP Music License Agreements and Reporting Forms.* en. url: http://www.ascap.com/music-users/licensefinder (visited on 12/10/2019).
{: fs-2}
***

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-1/">Introduction</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-2/">Part I)Background Research &gt; 1)Literature Review &gt; 1.1) Scoping Review</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-3/">1.2 Research Questions</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-4/">1.3 Report Structure</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-5/">1.4 Research Methodology</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-6/">1.5 Music Business Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-7/">1.6 Legal Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-8/">1.7 Automation Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-9/">1.8 Value Web Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-20/">2) Music Industry Supply Chain and Work Registration Standards</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-30/">3) Legal Frameworks Primer</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-40/">4) Music Licensing Primer</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-50/">5) Technology Primer</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-60/">Part II) Ricardian Contract &gt; 6) Motivation</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-70/">7) Decentralized Media Platforms</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-80/">8) Methods</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-90/">9) Discussion</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-100/">Conclusion</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-110/">References</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-120/">Appendix</a></li></ul>

***

</div>

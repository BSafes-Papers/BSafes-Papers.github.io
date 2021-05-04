---
layout: default
title: 9) Discussion  
parent: § Blockchain-mediated Licensing - Legal Engineering for Artist Empowerment  
grand_parent: Cryptocurrency 
nav_order: 900 
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

## 9 Discussion

### 9.1 Standard Form Design

We tailored the TML under the following circumstances:

- the licensor and licensee ("the parties") are very unlikely to have direct, one-on-one interactions;

- the parties are unlikely to be physically located in the same jurisdiction;

- the parties will have issues seeking legal recourse against each other;

- the licensor is seeking to offer non-exclusive licenses to the public;

- the licensor is likely a musician who is not connected with a record label;

- the licensor is unlikely to be a member of a CMO;

- the licensor is the holder of all rights under copyright of the musical work;

- the license should in the licensor's favor;

- the parties do not expect their transaction to be private;

- the parties have a basic understanding of Web3 technologies; and

- the parties have a basic understanding of copyright law.

In designing the TML, the major drafting decisions we made were:

- bundling all rights under copyright;

- tokenizing the licensor's rights under copyright ("copyright ownership");

- tokenizing the license grant to the licensee;

- requiring the licensee to obtain escrow from Kleros;

- requiring the parties to communicate through Status messenger;

- requiring the parties to accept Kleros Court as their only means for ADR;

- requiring the licensor to register with VerifiMedia to obtain an MVD- compliant digital file of the musical work;

- requiring the licensee to make a down payment in DAI;

- setting choice of law provisions for contract law, copyright law, and ADR; and

- adding recurring payments in Ether.

We decided to bundle all the rights under copyright the licensor may have together to try to avoid licensing coordination and fragmentation issues.<sup>990</sup> We decided to tokenize copyright ownership (i.e., make a digital representation of the licensor's copyright on the Ethereum blockchain) as an NFT and the license grant (i.e., make a digital representation of the licensee's license grant on the Ethereum blockchain) as an ERC-20 token. We chose to tokenize copyright ownership in the musical work as an NFT for two reasons:

- to track and assert copyright ownership to the musical work on-chain; and

- copyright ownership is a unique bundle of rights to a specific copyrighted work.

***
<sup>990</sup>Bodó, Gervais, and Quintais, Blockchain and smart contracts.
{: fs-2}
***

We chose to tokenize the license grant as an ERC-20 token for two reasons:
- to track the license grant under the licensor's copyright on-chain; and
- the license grant is on a non-exclusive basis (i.e., the license grant is not unique because anyone else can seek a license grant under the same terms).

Also, by tokenizing copyright ownership and the license grant, we hoped to address the licensing coordination discrepancy between o -chain and on-chain transactions.<sup>991</sup> Lastly, by tokenizing copyright ownership and the license grant, the parties can use their tokens to interact with the Ethereum blockchain ecosystem (e.g., other DApps and cryptocurrency exchanges).

We required the licensee to obtain escrow for the TML from Kleros. The escrow is for alleviating the harm from a breach of, or dispute under, the license for the bene t of the licensor. Additionally, by requiring on-chain escrow, we automated the acquisition and disposition of escrow, thus providing some cost-savings to the parties and keeping the interaction between the parties on-chain. 

We required the parties to communicate with each other concerning notices via the Status messenger DApp, so that the parties could securely communicate with each other using their on-chain identities (i.e., public addresses).<sup>992</sup>

We required the parties to agree and acknowledge the Kleros Court as the only ADR measure under the TML. By doing so, we wanted to ensure the parties could adjudicate their dispute on-chain because of the di culties of obtaining traditional legal recourse. Additionally, even after the resolution of the dispute in Kleros Court, the aggrieved party may still take their dispute to a court of competent jurisdiction. 

We required the down payment to be priced in USD and made in DAI, a stablecoin that is pegged one-to-one with the US dollar (USD), developed by MakerDAO, a Decentralized Finance (DeFi) credit facility (Alternatively, the down payment could be made with a centralized stablecoin such as Coinbase's USD Coin (USDC), Paxos Standard Token (PAX), or Gemini Dollar (GUSD), especially given the recent DeFi hacks between February and May 2020).<sup>993</sup> By requiring the down payment in DAI, the parties (and especially the licensor) can have some assurance that the down payment amount will remain relatively stable given normal market conditions.

We required recurring payments so that the licensor can have a small but reliable revenue stream from the TML. Unfortunately, the standard recurring payment smart contract on OpenLaw only allowed for payments in ETH.<sup>994</sup> We decided not to cap miner fees to a specific amount, and that such fees are excluded from any required payment amount (i.e., the licensee cannot include the miner fees as part of the payment amount). 

We included network congestion as an event under our Force Majeure clause so that the parties would not be punished for undue delay in carrying out their contractual obligations because the Ethereum blockchain network became so congested that miner fees became unreasonably too high or transactions could not be processed in a timely manner. 

We included governing law (i.e., choice of law) clauses for contract law, copyright law, and ADR. For contract law, we thought the choice law should be left to the licensor to decide.<sup>995</sup> For copyright law, we prohibited the

***
<sup>991</sup>Ibid.
{: fs-2}
<sup>992</sup>Additionally, the parties can communicate via email.
{: fs-2}
<sup>993</sup>Celia Wan. *In a first, MakerDAO protocol to auction MKR tokens to cover $4M bad debt.* en. Mar. 2020. url: https://www.theblockcrypto.com/post/58606/in-a-first-makerdao-protocol-to-auction-mkr-tokens-to-cover-4m-bad-debt (visited on 05/12/2020); Brady Dale and William Foxley. *DeFi Leader MakerDAO Weighs Emergency Shutdown Following ETH Price Drop*. en. Mar. 2020. url: https://www.coindesk.com/defi-leader-makerdao-weighs-emergency-shutdown-following-ethprice-drop (visited on 05/12/2020); DeFi Saver. Black Thursday at DeFi Saver. en. Mar. 2020. url: https://medium.com/defisaver/black-thursday-at-defi-saver-3c35ea6cd0d0 (visited on 05/12/2020).
{: fs-2}
<sup>994</sup>*Overview | OpenLaw Docs.*
{: fs-2}
<sup>995</sup>Though, we are considering adding default governing law options for contract law, such as the State of New York, in an updated version of the TML.
{: fs-2}
***

licensor from asserting any rights under copyright against the licensee other than those available under international copyright treaties.<sup>996</sup> For ADR, we chose the UNCITRAL model law on international commercial arbitration as the governing law.

Additionally, our design of the TML addressed the following concerns from the Literature Review in Part I<sup>997</sup>:

- Follow-on intent;

- Contractual capacity;

- Governing law;

- Electronic Transactions and Signatures;

- File formats for the musical work;

- Online dispute resolution; and

- Representing copyright on a blockchain.<sup>998</sup>

We addressed contractual capacity by explicitly stating in the Representations and Warranties section that the parties have the contractual capacity to enter into the agreement. We addressed follow-on intent by including a follow-on intent section where the parties expressly acknowledge that their intent to contract is carried over in the execution of any smart contracts embedded in the license. We addressed awareness of RCs, cryptographic systems, and Web3 technologies in the Recitals section by explicitly stating that the parties were aware of these risks. 

We addressed the digital file format concerns by requiring the licensor to complete the registration process with Verifi  Media to obtain a metadata bundle for the musical work, and give the licensee a copy of the musical work as digital audio file in the  .bc  file format so that the specific copy can be tracked.<sup>999</sup> Additionally, we included an anti-circumvention clause prohibiting the licensee from circumventing the protections of the metadata bundle.<sup>1000</sup>

We addressed the validity of electronic signatures in the licensee's or licensor's jurisdiction by requiring the parties to take any and all necessary steps to execute the TML, including providing a written signature if need be. 

We required that the TML should still be enforceable even if the licensee's jurisdiction does not recognize a signed and executed TML as valid. Though, this may be stretching enforceability and we caution the use of this clause.<sup>1001</sup>

We required the licensor to add ISRC- or ISWC-required information for the musical work to the TML. Even if the licensor does not have an ISRC or ISWC for the musical work (the licensor can submit N/A for this section), we thought it would still be valuable to require such information in the TML because it would:

- provide industry-standard metadata on the musical work, and

- be easier for music industry stakeholders to track transactions involving the musical work.

***
<sup>996</sup>We were also considering limiting the governing law for copyright to only those international copyright treaties (not as adopted in the domestic nation's laws) that have been adopted in their jurisdiction
{: fs-2}
<sup>997</sup>Some of these concerns were addressed previously when we discussed our major design decisions.
{: fs-2}
<sup>998</sup>Supra Section 1.
{: fs-2}
<sup>999</sup>This can be done in a more secure manner by having the licensor store the ".bc" formatted digital audio file on the IPFS, and using an access control smart contract to provide access to the licensee upon checking if the licensee has a license grant token.
{: fs-2}
<sup>1000</sup>Though, this may be unnecessary because of the WIPO Copyright Treaty (WCT).
{: fs-2}
<sup>1001</sup>Bodó, Gervais, and Quintais, "Blockchain and smart contracts".
{: fs-2}
***

Though, unfortunately, providing such information does not grant an ISRC or ISWC to the musical work. 

We included a privacy law provision to address when it was appropriate to process the personal data of the licensor, licensee, or both parties if one or both parties' personal data is subjected to a privacy law or regulation, such as the GDPR. Specifcally, our provision addressed whether there was a lawful basis for processing the licensee's personal data on the Ethereum blockchain if the licensee is an EU resident such that the GDPR would apply.

Our dispute resolution provision requires all disputes arising from, or related to, the license to be adjudicated in a Kleros Court (specifically, the E-commerce subcourt), with three (3) jurors, and the licensee must cover the Kleros deposit fee for arbitration.

We believe the TML satisfies the requirements of UETA and E-sign because the parties:

- have the intent to sign,

- are consenting to doing business electronically,

- are associating their signature (here being their cryptographic signatures via their public-private keys) with the TML on the Ethereum blockchain, and

- the record is retained on the Ethereum blockchain.

We also believe that the TML helps address the licensing costs and issues mentioned in the Music Licensing Primer.<sup>1002</sup> First, the TML helps address transaction costs (specifically negotiation, enforcement and matching costs) because the TML is pre-negotiated (terms of use and pricing), the embedded smart contracts execute and enforce the terms of the TML<sup>1003</sup>, any disputes arising between the parties can be addressed in Kleros Court<sup>1004</sup>), the executed TML is recorded on the Ethereum blockchain (and the tokens refer to the TML), and it is easier for musicians to find potential licensees in an international market.<sup>1005</sup> Second, the TML helps address membership costs by enabling musicians to directly license their works to an international market of potential licensees with the guaranties provided by Web3 technologies, thereby reducing the need to join a CMO, pay membership fees to CMOs, share revenue with CMOs, and license works on a collective basis.<sup>1006</sup> Third, the TML helps address multi-territorial issues by pre-determining the choice of law for copyright and ADR (specifically, restricting the choice of law to international treaties and rules), allowing the licensor to determine the jurisdiction for contract, and the TML is not restricted to any single territory. Fourth, the TML helps address contract management issues by retaining a record of the executed TML on the Ethereum blockchain (and the tokens refer to the TML), making the contracting process easier with the TML form and  ow, and making the TML publicly accessible on OpenLaw for any potential licensee to review.<sup>1007</sup>

OpenLaw also provides an option for private instances (private repositories to keep templates and agreements shielded from other users) which can address music industry stakeholder concerns about keeping their transactions confidential even when using blockchain and smart contracts.<sup>1008</sup> We chose not to exercise this option because our TML is a standard form that is meant to be accessible and modi able by anyone who is seeking to license musical works in a Web3 technologies context. Additionally, our TML can be modi ed to provide more transactional privacy (e.g., by removing the legend in the copyright and license grant tokens, or by using the TML in a private instance) if the parties desire more privacy.

***
<sup>1002</sup>4
{: fs-2}
<sup>1003</sup>However, this is debatable because the musical work does not automatically become available to the licensee upon signing. Though, this can be addressed by integrating the license with a DApp that fits such purposes.
{: fs-2}
<sup>1004</sup>Which is an easier option for the parties in a mass contracting context.
{: fs-2}
<sup>1005</sup>Bodó, Gervais, and Quintais, Blockchain and smart contracts; Handke and Towse, Economics of Copyright Collecting Societies; Towse, The Economic Effects of Digitization on the Administration of Musical Copyrights.
{: fs-2}
<sup>1006</sup>Handke and Towse, Economics of Copyright Collecting Societies.
{: fs-2}
<sup>1007</sup>*Top 8 Challenges in Contract Management.*
{: fs-2}
<sup>1008</sup>Torbensen and Ciriello, TUNING INTO BLOCKCHAIN.
{: fs-2}
***

Our TML could work well with COALA-IP's licensing protocol because each transaction with the TML is hashed on the Ethereum blockchain, and this hash can be used in an IPLD or JSON-LD format to refer to the TML and if possible, associate it with the digital audio file's hash on the IPFS (which would be a Content Identifier (CID)).<sup>1009</sup> The TML could be described by COALA-IP's IP licensing protocol with the following models:

- Place,

- Party,

- Creation,

- Right, and

- Assertion.<sup>1010</sup>

Place could aid in determining the territory where the copyrighted work was created.<sup>1011</sup> Party could be used for the Licensor to provide personally identifiable information.<sup>1012</sup> Creation could be used to describe the copyrighted work and any copies of the copyrighted work.<sup>13</sup> Right could be used to describe the nature of the transaction involving the TML.<sup>1014</sup> Lastly, Assertion could be used as a failsafe for notifying third-parties about the licensor's claim as an author or rightsholder of the copyrighted work, and thus it may be challenged in the future.<sup>1015</sup>

We defined the following terms in the TML:

- 51% attack;

- Cryptographic Signature;

- DAI stablecoin;

- Network Congestion;

- Non-fungible Token;

- DApp;

- Fungible Token;

- Moral Rights;

- Blockchain;

- Blockchain Platform;

- Smart Contract;

- Token Transfer;

- Kleros Escrow; and

- Kleros Court.

Most of the terms we de ned are generally applicable to any RC-Web3 Template. 

A concern we noted that could arise from RC-Web3 Templates is jurisdiction shopping. We became primarily concerned with jurisdiction shopping (generally for favorable laws) where the parties (more often than not, the licensor) will seek to  nd jurisdiction(s) with the most favorable legal frameworks and venues (primarily online) to themselves, and thereby avoid scrutiny from their own jurisdiction's legal system.

***
<sup>1009</sup>*COALAIP/specs.*
{: fs-2}
<sup>1010</sup>Ibid.
{: fs-2}
<sup>1011</sup>Ibid.
{: fs-2}
<sup>1012</sup>Ibid.
{: fs-2}
<sup>1013</sup>Ibid.
{: fs-2}
<sup>1014</sup>Ibid.
{: fs-2}
<sup>1015</sup>Ibid.
{: fs-2}
***

### 9.2 Research Limitations
Unfortunately, time constraints prevented us from fully exploring automated legal applications of music licenses could not cover everything we wanted to consider as we were working on this report (which also makes this list a good starting point for future research). 

Specifically, we did not have enough time to fully investigate:

- Creating an OpenLaw-integrated DApp;

- Connecting an OpenLaw Agreement with a Chainlink data oracle (i.e., embedding a Chainlink smart contract connected to an external data feed in our license);

- Developing a Semantic Web music license;

- Developing an RC-Web3 Template that interacts with the Semantic Web;

- Developing an RC-Web3 Template pursuant to COALA-IP's Licensing Protocol documentation;

- Determining RC-Web3 Template compliance with non-GDPR privacy laws and regulations;

- Creating a RC-Web3 Template for compulsory licensing;
- Having legal practitioners, music industry stakeholders, and technologists test and critique the PTD method and the TML;

- Practicing the TT and AT core design practices with the TML;

- Determining the interaction between national and international arbitration rules and procedures in an online context;

- Developing an access control smart contract to control access to the digital music file in the ".bc" format stored on a distributed data storage solution such as the IPFS, and embedding this smart contract in the TML;

- Discussing the ADR rules and procedures in the USA, EU, and international contexts in greater detail;

- Discussing Chainlink's data oracle network and services;

- How independent labels would design an automated music license;

- Developing an access control smart contract for transferring or possibly burning the copyright and license grant tokens that could be controlled by the Kleros Court in resolving a dispute;

- Determining an appropriate international standard for contract law in a RC-Web3 Template context;

- Investigating remedies available under other areas of law such as tort law;

- Investigating further how the TML can be used in conjunction with COALA-IP's IP licensing protocol to secure the TML across multiple ledgers and the web, especially regarding user extensions to the IP licensing protocol;

- Incorporating other legal technology products with OpenLaw templates and forms; and

- Explicitly adding a termination smart contract to the license.


### 9.3 Future Research Areas
For future research in this research topic, we recommend investigating the following areas:

- Connecting an OpenLaw RC-Web3 Template with a Chainlink data oracle (i.e., embedding a Chainlink smart contract connected to an external data feed in a Ricardian Contract);

- Creating a music licensing DApp that is legally compliant;

- Dynamic pricing of musical works via token bonding curves (aka automated market makers);

- Determining Ricardian Contract compliance with GDPR and other data privacy laws and regulations;

- Use of decentralized identifiers (DID) and self-sovereign identity (SSID) platforms such as uPort for identifying the parties to an agreement;

- Comparing blockchain's usability for copyright transfers to copyright licenses;

- How to apply zero-knowledge proofs (ZKP) to provide transactional privacy for RC-Web3 Templates;

- How a Decentralized (or Distributed) Autonomous Organization (DAO) such as DAOrecords<sup>1016</sup> could act as a CMO for licensing musical works via RC-Web3 Templates while remaining accountable to its members; and

- Further exploring how token engineering can be applied to the music industry.

***
<sup>1016</sup>*Introducing DAOrecords " DAOrecords.* en-US. url: https://www.daorecords.org/about-us/ (visited on 06/02/2020).
{: fs-2}
***

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-1/">Introduction</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-2/">Part I)Background Research &gt; 1)Literature Review &gt; 1.1) Scoping Review</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-3/">1.2 Research Questions</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-4/">1.3 Report Structure</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-5/">1.4 Research Methodology</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-6/">1.5 Music Business Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-7/">1.6 Legal Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-8/">1.7 Automation Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-9/">1.8 Value Web Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-20/">2) Music Industry Supply Chain and Work Registration Standards</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-30/">3) Legal Frameworks Primer</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-40/">4) Music Licensing Primer</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-50/">5) Technology Primer</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-60/">Part II) Ricardian Contract &gt; 6) Motivation</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-70/">7) Decentralized Media Platforms</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-80/">8) Methods</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-90/">9) Discussion</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-100/">Conclusion</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-110/">References</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-120/">Appendix</a></li></ul>

***

</div>

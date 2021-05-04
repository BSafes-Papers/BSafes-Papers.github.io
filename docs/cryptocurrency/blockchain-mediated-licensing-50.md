---
layout: default
title: 5) Technology Primer
parent: § Blockchain-mediated Licensing - Legal Engineering for Artist Empowerment  
grand_parent: Cryptocurrency 
nav_order: 500 
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

## 5 Technology Primer
In discussing the background on our research topic, we also decided to include a primer on the technologies (with an emphasis on Web3 technologies) applicable to automated music licensing. The technology primer will provide a basic information on:

- Blockchain;

- Smart Contracts;

- InterPlanetary File System;

- Application Programming Interfaces;

- Data Oracles;

- Decentralized Applications;

- Digital Assets;

- Non-fungible Tokens;

- Linked Data;

- Ricardian Contracts; and

- Kleros's ADR Protocol.

### 5.1 Blockchain
Blockchain<sup>781</sup> is an append-only database, often described as a trustless (also referred to as trust-minimization a or low-trust) system, that is secured by a peer-to-peer (p2p) computer network.<sup>782</sup> In the network, the blockchain is replicated so that each node has a copy of the blockchain.<sup>783</sup> The main advantage of a blockchain is that it allows counterparties to transact in a secure manner without the need for a trusted third (or centralized) party.<sup>784</sup> The term  blockchain  originates from Satoshi Nakamoto's whitepaper, *Bitcoin: A Peer-to-Peer Electronic Cash System,* though Satoshi Nakamoto never mentions the word blockchain in the whitepaper to describe the blockbased data structure.<sup>785</sup>

The blockchain data structure is an ordered list of blocks that each reference the previous block by the previous block's cryptographic hash.<sup>786</sup>  Each block consists of a set of transactions<sup>787</sup>. <sup>788</sup> Once a new block is mined, each node will add the newly mined block to their copy of the blockchain.<sup>789</sup> Once a block is appended to the blockchain, the newly-appended block cannot be removed or modi ed as to ensure the blockchain's data integrity.<sup>790</sup>

***
<sup>781</sup>Treiblmaier, "Toward More Rigorous Blockchain Research"; Julie Maupin, Jonas Kahlert, and Timo Honsel. "Blockchain: A World Without Middlemen?" In: 2019 (Blockchain is often used synonymously or interchangeably with Distributed Ledger Technology (DLT) and Horst Treiblmaier recommends also mentioning the term when discussing blockchain.).
{: fs-2}
<sup>782</sup>Bodó, Gervais, and Quintais, "Blockchain and smart contracts"; M.E. Burge. "Apple pay, bitcoin, and consumers: The ABCs of future public payments law". In: *Hastings Law Journal 67* (Aug. 2016), pp. 1493"1550.
{: fs-2}
<sup>783</sup>Alharby and Moorsel, "Blockchain Based Smart Contracts : A Systematic Mapping Study".
{: fs-2}
<sup>784</sup>Ibid.
{: fs-2}
<sup>785</sup>Alharby and Moorsel, "Blockchain Based Smart Contracts : A Systematic Mapping Study"; Satoshi Nakamoto. "Bitcoin: A Peer-to-Peer Electronic Cash System". In: *Cryptography Mailing list at https://metzdowd.com* (Oct. 2008); Treiblmaier, "Toward More Rigorous Blockchain Research"; Haugen and Engebretsen, "The Music Industry on Blockchain Technology".
{: fs-2}
<sup>786</sup>Alharby and Moorsel, "Blockchain Based Smart Contracts : A Systematic Mapping Study".
{: fs-2}
<sup>787</sup>Transactions is often used synonymously with data.
{: fs-2}
<sup>788</sup>Alharby and Moorsel, "Blockchain Based Smart Contracts : A Systematic Mapping Study".
{: fs-2}
<sup>789</sup>Haugen and Engebretsen, "The Music Industry on Blockchain Technology".
{: fs-2}
<sup>790</sup>Alharby and Moorsel, Blockchain Based Smart Contracts : A Systematic Mapping Study; Burge, Apple pay, bitcoin, and consumers: The ABCs of future public payments law; Garry Gabison. Policy Considerations for the Blockchain Technology Public and Private Applications. In: *Southern Methodist University Science & Technology Law Review 19* (3 Aug. 2016), pp. 327350; Jake Frankenfield. Cryptocurrency. en. url: https://www.investopedia.com/terms/c/cryptocurrency.asp (visited on 12/19/2019).
{: fs-2}
***

The first blockchain implementation, Bitcoin, mitigated two major problems:

1. double spending<sup>791</sup> , and

2. eliminating fraud, through the Proof of Work (PoW) mining algorithm and the Longest Chain Rule consensus algorithm<sup>792</sup> process.<sup>783</sup>

Mining is the process of authenticating and adding blocks of transactions to the blockchain, and is a means of stopping spam (i.e., anti-sybil measure).<sup>794</sup>Nodes on the p2p network mine (These specific nodes are called "miners ) attempt to solve a complex math problem by ordering transactions in a manner to have the hash of the block have a certain number of leading zeros.<sup>795</sup> Once the problem is solved, the block can then be added to the Bitcoin blockchain.<sup>796</sup> In exchange for authenticating and adding a block, miners are rewarded with new Bitcoins.<sup>797</sup>

To ensure that each node has the correct copy of the blockchain without a trusted intermediary, the Bitcoin blockchain also implements the Longest Chain Rule, a consensus algorithm on the state of the Bitcoin blockchain.<sup>798</sup> In simplest terms, the longest chain rule will steer the nodes on the Bitcoin p2p network towards the blockchain which has the most work done, i.e., the chain that has the most computational effort supplied.<sup>799</sup>

The hash of each block maintains the integrity of the data stored in the blockchain.<sup>800</sup> In a hashing algorithm, the input is an arbitrary amount of data that is mapped to an output of a unique, fixed-size number of bytes.<sup>802</sup> Since the output is unique for each input, it is nearly impossible to get the same hash for two different inputs.802 A new block primarily holds a set of transactions, an index, a timestamp, and a header.<sup>803</sup> In the block header, there are two hashes:

1. the previous block's hash, and

2. the current block's hash.<sup>804</sup>

By requiring new blocks to reference the hash of the previous block, we obtain an immutable, sequential chain of transactions.<sup>805</sup> If someone tried to change the contents of a block, that particular block's cryptographic hash would change, and this would change the hashes of all the sequential blocks after the altered block.<sup>806</sup> Thus, it becomes nigh impossible for one party to commit fraud because a fraudster would need to alter the copy of the blockchain for  fifty-percent or greater (>50%) of the nodes, and that's before a new block gets added to the blockchain .<sup>807</sup>

Horst Treiblmaier in *Toward More Rigorous Blockchain Research: Recommendations for Writing Blockchain Case Studies,* summarized the most important characteristics of blockchain as:

***
<sup>791</sup>Burge, Apple pay, bitcoin, and consumers: The ABCs of future public payments law.
{: fs-2}
<sup>792</sup>Referring specifically to Bitcoin's Proof-of-Work mining algorithm and Longest Chain consensus algorithm.
{: fs-2}
<sup>793</sup>Haugen and Engebretsen, The Music Industry on Blockchain Technology; Burge, Apple pay, bitcoin, and consumers: The ABCs of future public payments law; Frankenfield, Cryptocurrency.
{: fs-2}
<sup>794</sup>Gabison, Policy Considerations for the Blockchain Technology Public and Private Applications; Burge, Apple pay, bitcoin, and consumers: The ABCs of future public payments law; Frankeneld, Cryptocurrency.
{: fs-2}
<sup>795</sup>Johannes Mueller. *Building Blockchains* in R. Feb. 2018. url: https : / / www . datacamp . com / community / tutorials /blockchain-r (visited on 12/20/2019).
{: fs-2}
<sup>796</sup>Ibid.
{: fs-2}
<sup>797</sup>bid.
{: fs-2}
<sup>998</sup>Ibid.
{: fs-2}
<sup>799</sup>bid.
{: fs-2}
<sup>800</sup>Ibid.
{: fs-2}
<sup>801</sup>Patrick Schueduel, Nikolaj Groeneweg, and Baldegger Rico. The Crypto Encyclopedia: Coins, Tokens and Digital Assets from A to Z. Aug. 2019. isbn: 978-2-940384-47-1.
{: fs-2}
<sup>802</sup>Mueller, *Building Blockchains in R.*
{: fs-2}
<sup>803</sup>Ibid.
{: fs-2}
<sup>804</sup>Ibid.
{: fs-2}
<sup>805</sup>Ibid.
{: fs-2}
<sup>806</sup>Mueller, *Building Blockchains in R.*
{: fs-2}
<sup>807</sup>bid. (Small window of time to make that happen, especially since a new  block is added to the Bitcoin blockchain every ten (10) minutes.).
{: fs-2}
***

- "[i]mmutability",

- "[t]ransparency",

- "[p]rogrammability",

- "[d]ecentralization",

- "[c]onsenus", and

- "[d]istributed trust."<sup>808</sup>

Blockchains can be categorized based on a permission typology.<sup>809</sup> In the permission typology, there are two types of blockchains, permissioned and permissionless<sup>810</sup> A permissionless blockchain is a blockchain in which anyone may read (examine transactions contained in blocks) and write (submit a transaction to be stored in a block) to the blockchain.<sup>811</sup> A permissioned blockchain is a blockchain in which there is a restriction on who can read and/or write to the blockchain<sup>812</sup> The issues with the current state of blockchain architecture, mentioned in the literature and in the industry, are readily summarized by Treiblmaier, and reproduced here for convenience:

- "Throughput: Number of transactions being processed within a specific period of time.

- Latency: Amount of time before a transaction is processed.

- Size and bandwidth: The Blockchain grows over time as new blocks are constantly added. This also consumes considerable bandwidth for downloading data.

- Wasted resources: Blockchain-intrinsic inefficiencies such as redundant data transmission, storage and energy-consuming consensus protocols.

- Usability Users': interactions with Blockchain applications.

- Versioning: Hard forks, multiple chains. A multitude of Blockchain versions and forks facilitate attacks and hamper cross-transactions.

- Privacy: The right to control access to (personal) information as well as to delete it.

- Evidentiary quality: Trustworthiness of Records; Questions pertaining to the truthfulness of content on the Blockchain.

- Lack of Standards: No standards have emerged yet for access rights, data structures and allowable transactions.

- Regulations: Legislation is lagging behind technological development.

- Shared governance: Blockchain solutions call for new structures that might disrupt existing governance.

- Viable ecosystem: The attraction of a critical mass of adopters.

- Attack Surface: The Blockchain as a target of potential attacks."<sup>813</sup>

The blockchain characteristics we explicitly sought to utilize in our research and in the creation of our Tokenized Music License (TML) were:

- Immutability,

- Transparency,

***
<sup>808</sup>Treiblmaier, "Toward More Rigorous Blockchain Research".
{: fs-2}
<sup>809</sup>Ibid.
{: fs-2}
<sup>810</sup>Ibid.
{: fs-2}
<sup>811</sup>Ibid.
{: fs-2}
<sup>812</sup>Treiblmaier, "Toward More Rigorous Blockchain Research".
{: fs-2}
<sup>813</sup>Ibid.
{: fs-2}
***

- Programmability, and

- Decentralization.<sup>814</sup>

We desired the immutability characteristic because we wanted to ensure that once an agreement is signed by the parties, the record of the transaction and signatures thereto cannot be modi ed in the future.<sup>815</sup>

We desired the transparency characteristic because we wanted to make transactions with the TML publicly accessible so that potential parties can have a negotiating reference from the prior negotiations of other parties, to have proof that a transaction occurred and was validated, to help musicians and users have knowledge of and seek out the TML, and to mitigate against potential disputes arising over the content of the license (not necessarily the interpretation of the license) or confusion regarding whether a license has been signed.<sup>816</sup>

We desired the programmability characteristic because we wanted to utilize smart contracts to guarantee the fulfillment of certain objective demands and requirements envisioned in the TML, optimize the licensing process by alleviating licensing costs and issues, and the need to ensure that the smart contracts embedded in the TML will execute with little to no worry for down-time.<sup>817</sup>

We desired the decentralization characteristic because we believe decentralization will enable musicians to gain a greater foothold in the music industry's value web by reducing the number of intermediaries needed to license their works. We expect that this will lead to fairer remuneration for musicians and will help alleviate concerns of collusion among music industry stakeholders whose interests do not align with the interests of musicians.<sup>818</sup>

### 5.2 Smart Contracts
A smart contract is executable code stored on a blockchain to facilitate agreements among two or more parties that will automatically execute based on a set of prede ned conditions.<sup>819</sup> The idea of smart contracts came from Nick Szabo in 1994.<sup>820</sup> According to Nick Szabo, despite the digital era creating entirely new tools, applying the known concepts of contract law may be key, given the rapid development of the modern world:  By extracting from our current laws, procedures, and theories those principles which remain applicable in cyberspace, we can retain much of this deep tradition, and greatly shorten the time needed to develop useful digital institutions."<sup>821</sup>As Dariusz Szostek points out, smart contracts were de ned by the UK Government in 2016 in the report titled  Distributed Ledger Technology: beyond block chain , where smart contracts were de ned as  contracts whose terms are recorded in a computer language instead of legal language (...) can be automatically executed by a computing system, such as a suitable distributed ledger system [and having the bene ts of] low contracting, enforcement, and compliance costs; consequently it becomes economically viable to form contracts over numerous low-value transactions. <sup>822</sup> Smart contracts did not truly become a viable option until the emergence of blockchain technology, and especially the Ethereum blockchain.

***
<sup>814</sup>Ibid.
{: fs-2}
<sup>815</sup>Ibid.
{: fs-2}
<sup>816</sup>Ibid.
{: fs-2}
<sup>817</sup>Ibid.
{: fs-2}
<sup>818</sup>Treiblmaier, "Toward More Rigorous Blockchain Research"; Bodó, Gervais, and Quintais, "Blockchain and smart contracts; Sitonio and Nucciarelli, "The Impact of Blockchain on the Music Industry.
{: fs-2}
<sup>819</sup>*Smart Contracts*. en-US. url: https://blockchainhub.net/smart-contracts/ (visited on 10/18/2019).
{: fs-2}
<sup>820</sup>Alharby and Moorsel, Blockchain Based Smart Contracts : A Systematic Mapping Study.
{: fs-2}
<sup>821</sup>Nick Szabo. *Formalizing and Securing Relationships on Public Networks | Satoshi Nakamoto Institute.* url: https : / / nakamotoinstitute.org/formalizing-securing-relationships/ (visited on 10/18/2019).
{: fs-2}
<sup>822</sup>U.K. Government Chief Scientific Adviser. *Distributed Ledger Technology: beyond block chain.* Tech. rep. Government Oce of Science, 2016. url: https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/492972/gs-16-1-distributed-ledger-technology.pdf.
{: fs-2}
***

### 5.3 InterPlantery File System (IPFS)
 Distributed data storage is data stored among multiple devices rather than a single device. <sup>823</sup>  Distributed peer-to-peer (p2p) data storage is a type of distributed storage where data is shared among the nodes on a p2p network. <sup>824</sup>  The InterPlanetary File System (IPFS) is a project by Filecoin that enables distributed storage and transfer of files among nodes in a peer-to-peer network. <sup>825</sup>  In the IPFS,  file storage is distributed among the nodes on the network such that each node has a chunk of the file data, thereby ensuring that no single node holds a complete copy of a file. <sup>826</sup>  To achieve the above, the IPFS implements a [D]istributed [H]ash [T]able (DHT) that allows "any participating node to efficiently retrieve the value associated with a given key."  <sup>827</sup>  By relying on a p2p network, the DHT can scale to an "extremely large numbers of nodes and to handle continual node departures, arrivals and failures."  <sup>828</sup>  A major advantage of using the IPFS is that it ensures that a node requesting a file will receive it from the closest nodes storing the file, thereby making file retrieval faster. <sup>829</sup>
 
### 5.4 Application Programming Interface (API) and Data Oracles
An application programming interface (API) is a software intermediary that allows interaction between two distinct software programs, i.e., how one software application can request another software application to provide a service.<sup>830</sup> In general, API often refers to web-based APIs, APIs that provide a connectivity interface for applications to communicate with servers over web protocols such as Hypertext Transfer Protocol (HTTP), and the use of JavaScript Object Notation (JSON) format.<sup>831</sup> For example, when an end user authenticates their identity on a software application via their Facebook pro le or email address, they are utilizing an API that interfaces between the software application and Facebook or their email provider.<sup>832</sup>

There are three types of APIs:

1. public,

1. private, and

1. partnership.<sup>833</sup>

A public API is an API that is accessible to developers or the public (developers, startups, governments, etc.) on a free or structured freemium basis (e.g., a limited number of API calls per month).<sup>834</sup> A private API is an API that is only used internally within an organization.<sup>835</sup> A partner API is a platform-esque API that multiple organizations can integrate within their systems.<sup>836</sup>

***
<sup>823</sup>Ledgerback Cooperative. *My Data! My Rules!* en. Sept. 2019. url: https://medium.com/the-backers/my-data-my-rules60890ffa0e56 (visited on 12/20/2019); Eugene Cheah. Explain Distributed Storage - and how it goes down for github / uilicious / cloud / etc. en. url: https://dev.to/uilicious/explain-distributed-storage---and-how-it-goes-down-for-github--uilicious--cloud--etc-1mni (visited on 12/20/2019).
{: fs-2}
<sup>824</sup>Cooperative, *My Data! My Rules!;* Cheah, *Explain Distributed Storage - and how it goes down for github / uilicious / cloud / etc.*
{: fs-2}
<sup>825</sup>Cooperative, *My Data! My Rules!;* Cheah, *Explain Distributed Storage - and how it goes down for github / uilicious / cloud / etc.*
{: fs-2}
<sup>826</sup>*Cooperative, My Data! My Rules!;* Cheah, *Explain Distributed Storage - and how it goes down for github / uilicious / cloud / etc.*
{: fs-2}
<sup>827</sup>*Cooperative, My Data! My Rules!;* Cheah, *Explain Distributed Storage - and how it goes down for github / uilicious / cloud / etc.*
{: fs-2}
<sup>828</sup>*Cooperative, My Data! My Rules!;* Cheah, *Explain Distributed Storage - and how it goes down for github / uilicious / cloud / etc.
{: fs-2}
<sup>829</sup>*Cooperative, My Data! My Rules!;* Cheah, *Explain Distributed Storage - and how it goes down for github / uilicious / cloud / etc.*
{: fs-2}
<sup>830</sup>*What is an API? (Application Programming Interface).* en. url: https://www.mulesoft.com/resources/api/what-is-an-api (visited on 10/18/2019).
{: fs-2}
<sup>831</sup>Ibid.
{: fs-2}
<sup>832</sup>Ibid.
{: fs-2}
<sup>833</sup>*What is an API?*. en-US. url: https://nordicapis.com/focus-topics/what-is-an-api/ (visited on 10/18/2019).
{: fs-2}
<sup>834</sup>Ibid.
{: fs-2}
<sup>835</sup>*What is an API?.*
{: fs-2}
<sup>836</sup>Ibid.
{: fs-2}
***

Data oracles ("oracles") are data providers, akin to application programming interfaces (APIs), that input external information into smart contracts on a blockchain.<sup>837</sup> Oracles are very powerful because they not only control what information gets inputted into the blockchain, they also determine which functions a smart-contract will execute in response to the information<sup>838</sup>

### 5.5 Decentralized Applications (DApps)
Decentralized applications (commonly known as dApps or DApps, but for this report, DApp shall be used) are becoming increasingly popular in the blockchain ecosystem, and are deemed the biggest application of smart contract platforms such as Ethereum and EOS.<sup>839</sup> DApps are applications that run on peer-to-peer (P2P) computer networks, and for our purposes, applications that run on a blockchain P2P network.<sup>840</sup>DApps provide several advantages over traditional web applications, such as decentralization (no single entity can shut it down) and open source (the source code is available to the public).<sup>841</sup> Blockchain DApps, at least in their current form, are Web3-enabled websites (websites that interact with blockchains) that use smart contracts and the blockchain as the backend for web applications .<sup>842</sup>

### 5.6 Digital Assets
We shall introduce three types of digital assets:

1. cryptocurrencies,

1. tokens, and

1. stablecoins.

A cryptocurrency (also known as a coin) is a digital token (often the  rst token and is considered the native token) created on a blockchain, that operates as a medium of exchange, in which supply growth is constrained through mining or a similar process.<sup>843</sup> A token is a digital token created on a blockchain, that is a digital representation of a real or virtual asset, rights, or unit of value<sup>844</sup> Common token standards are ERC-20 and ERC-721 on the Ethereum blockchain.<sup>845</sup> A stablecoin is a digital token that is collateralized by an underlying asset to maintain a relatively stable price.<sup>846</sup>

### 5.7 Non-fungible Tokens (NFTs)
Non-fungible<sup>847</sup> tokens (NFTs) are unique tokens meant to represent digital assets, commonly based on the ERC-721 standard, that have a "name, a description, and a URI."<sup>848</sup> The ERC-721 is a standard on the Ethereum

***
<sup>837</sup>Delphi. *The Oracle Problem*. en. July 2017. url: https : / / medium . com / @DelphiSystems / the - oracle - problem -856ccbdbd14f (visited on 10/18/2019).
{: fs-2}
<sup>838</sup>bid.
{: fs-2}
<sup>839</sup>Rick D. *Number of DApps on Ethereum and EOS Soaring, Yet Usage Lags.* en-US. Jan. 2019. url: https://www.newsbtc.com/2019/01/07/dapps-ethereum-eos/ (visited on 10/18/2019).
{: fs-2}
<sup>840</sup>*What is a dApp? Decentralized Application on the Blockchain.* en-US. url: https://blockchainhub.net/decentralizedapplications-dapps/ (visited on 10/18/2019).
{: fs-2}
<sup>841</sup>Ibid.
{: fs-2}
<sup>842</sup>Ibid.
{: fs-2}
<sup>843</sup>*What is Cryptocurrency. Guide for Beginners*. en. url: https://cointelegraph.com/bitcoin-for-beginners/what-arecryptocurrencies (visited on 10/18/2019); Schueel, Groeneweg, and Rico, *The Crypto Encyclopedia: Coins, Tokens and Digital Assets from A to Z.*
{: fs-2}
<sup>844</sup>Haugen and Engebretsen, "The Music Industry on Blockchain Technology; Schueduel, Groeneweg, and Rico, *The Crypto Encyclopedia: Coins, Tokens and Digital Assets from A to Z*(Though, tokens can be used to represent anything.).
{: fs-2}
<sup>845</sup>Haugen and Engebretsen, "The Music Industry on Blockchain Technology".
{: fs-2}
<sup>846</sup>Kyle Ellicott. *An Overview of Stablecoins.* en. Sept. 2019. url: https://medium.com/coinmonks/an-overview-of-stablecoins-fed7553fb25b (visited on 12/20/2019).
{: fs-2}
<sup>847</sup>Haugen and Engebretsen, "The Music Industry on Blockchain Technology" ("[Non-f]ungible refers to something that can[not] be replaced by another item.").
{: fs-2}
<sup>848</sup>John Gordon. *NIFTY Blockchain Gaming Thoughts.* en. Aug. 2018. url: https://medium.com/@jagordon/nifty-blockchain-gaming-thoughts-92075a4f934a (visited on 10/18/2019).
{: fs-2}
***

blockchain that  defines a minimum interface a smart contract must implement to allow unique tokens to be managed, owned, and traded. <sup>849</sup> NFTs are generally created for one-of-a-kind collectibles, and can represent anything ranging from art, in-game items, tickets, to even digital pets (e.g., CryptoKitties)<sup>850</sup>

Other than the ERC-721 standard, there is also the ERC-1155 and ERC-998 standards for NFTs.<sup>851</sup> The ERC-1155 standard was developed by Enjin, a blockchain videogames and wallet company.<sup>852</sup> ERC-1155 standard allows the ID  eld to represent a class of assets, rather than a single asset.<sup>853</sup> The advantage over ERC-721 that ERC-1155 provides is that it is cheaper to transfer multiple assets (e.g., a single transfer operation to transfer 1,000 items, rather than 1,000 transfer options to transfer 1,000 items).<sup>854</sup> The disadvantage is that it is no longer possible to track a single asset within the class<sup>855</sup> The ERC-998 standard (aka Composables), is a standard that allows NFTs to own other digital assets (non-fungible and fungible).<sup>856</sup>

### 5.8 Linked Data
Linked Data (LD) is a design approach to connect machine-readable, interlinked resources across the Semantic Web, i.e., the web of data, via technologies such as Uniform Resource Identifiers (URIs) and the Resource Description Framework (RDF).<sup>857</sup> The Semantic Web refers to an extended functionality of the WorldWideWeb where data is interlinked and machine-readable by adding additional data descriptors to existing content on the web.<sup>858</sup> URIs are unique identifiers for any type of content or data utilizing a single global identification system.<sup>859</sup> RDF is a model for data publishing and interchange developed by the WorldWideWeb Consortium (W3C).<sup>860</sup> In RDF, all data is published in a database as a triplestore. Triplestores materialize the links between data through a subject, predicate (or verb) and object linked model (subject > predicate > object).<sup>861</sup>

The four principles of LD are:

1. "Use URIs as names for things";

1. "Use HTTP URIs so that people can look up these names";

1. "When someone looks up a URI, provide useful information, using  standards (RDF, SPARQL)"; and

1. "Include links to other URIs so that they can discover more things."<sup>862</sup>

An example project working with Linked Data is SoLiD, another project by Sir Tim Berners Lee, in which the LD approach defines the relationships among data by:

- by having a uniform resource location (URL) for each piece of data, and

- explicitly stating how each piece of data is related to each other.<sup>863</sup>

***
<sup>849</sup>*ERC-721*. url: http://erc721.org/ (visited on 10/18/2019).
{: fs-2}
<sup>850</sup>Gordon, *NIFTY Blockchain Gaming Thoughts.*
{: fs-2}
<sup>851</sup>dfinzer. *The Non-Fungible Token Bible: Everything you need to know  about NFTs*. en-US. Jan. 2020. url: https://opensea.io/blog/guides/non-fungible-tokens/ (visited on 05/15/2020).
{: fs-2}
<sup>852</sup>Ibid.
{: fs-2}
<sup>853</sup>Ibid.
{: fs-2}
<sup>854</sup>Ibid.
{: fs-2}
<sup>855</sup>Ibid.
{: fs-2}
<sup>856</sup>Ibid.
{: fs-2}
<sup>857</sup>*What are Linked Data and Linked Open Data?* en-US. url: https://ontotext.com/knowledgehub/fundamentals/linkeddata-linked-open-data/ (visited on 09/14/2019); Introduction to the Solid Specication | Solid.
{: fs-2}
<sup>858</sup>*What Is the Semantic Web?* en-US. url: https://ontotext.com/knowledgehub/fundamentals/what-is-the-semanticweb/ (visited on 09/14/2019).
{: fs-2}
<sup>859</sup>*What are Linked Data and Linked Open Data?*
{: fs-2}
<sup>860</sup>*What is RDF Triplestore?* en-US. url: https://ontotext.com/knowledgehub/fundamentals/what-is-rdf-triplestore/
(visited on 09/14/2019).
{: fs-2}
<sup>861</sup>Ibid.
{: fs-2}
<sup>862</sup>*What are Linked Data and Linked Open Data? *; Sir Tim Berners Lee. *Linked Data - Design Issues.* url: https://www.w3.org/DesignIssues/LinkedData.html (visited on 10/18/2019).
{: fs-2}
<sup>863</sup>*What are Linked Data and Linked Open Data?* ; Lee, *Linked Data - Design Issues; Introduction to the Solid Specication | Solid*
{: fs-2}
***

### 5.9 Ricardian Contracts
Ricardian Contracts (RC) are semi-automated, human- and machine-readable contracts that are expressed and executed as software, with the parties signing the contract via cryptographic signatures<sup>864</sup> RCs were first conceptualized by Ian Grigg in 1995.<sup>865</sup> RCs utilize markup language for combining legal prose with machinereadable tags.<sup>866</sup> The goal is to automate generally objective terms so that they may be performed by software programs, while leaving subjective language to be determined by the parties.<sup>867</sup>

The Accord Project, OpenLaw, Clause, and other similar projects are developing software stacks and standards for RCs.<sup>868</sup> With the emergence of such software, users will be able to draft legal prose in markup language that interacts with blockchains, the Semantic Web, and other software.<sup>869</sup> Though these platforms are in their infancy, they represent the potential for RCs to dramatically change contract management.<sup>870</sup> DocuSign, a member of the Ethereum Enterprise Alliance and the Accord project, has implemented two RC-related services that interact with the Ethereum blockchain.<sup>871</sup> The first service is a document verification service that allows anyone to verify a DocuSign agreement exists (or compare the authenticity of a copy of the agreement) via a hash of the original DocuSign agreement stored on the Ethereum blockchain.<sup>872</sup> The second service is providing a Trust Service Provider model for projects that work on digital identity management to integrate their blockchain application with DocuSign's platform.<sup>873</sup>

***
<sup>864</sup>Chohan, "What Is a Ricardian Contract?"
{: fs-2}
<sup>865</sup>Ricardian contracts: A smarter way to do smart contracts? en. url: https://www.schoenherr.eu/publications/publication-detail/ricardian-contracts-a-smarter-way-to-do-smart-contracts/ (visited on 10/18/2019); Dmitri Koteshov. Smart vs. Ricardian Contracts: What's the Dierence? en-US. Feb. 2018. url: https://www.elinext.com/industries/financial/trends/smart-vs-ricardian-contracts/ (visited on 10/18/2019); I. Grigg. "The Ricardian contract". In: Proceedings. First IEEE International Workshop on Electronic Contracting, 2004. San Diego, CA, USA: IEEE, 2004, pp. 25"31. isbn: 9780769521848. doi: 10.1109/WEC.2004.1319505. url: http://ieeexplore.ieee.org/document/1319505/ (visited on 10/18/2019).
{: fs-2}
<sup>866</sup>Ricardian contracts; Dmitri Koteshov, Smart vs. Ricardian Contracts; Grigg, "The Ricardian contract"; What is a Ricardian Contract? en. July 2017. url: https://www.r3.com/blog/what-is-a-ricardian-contract/ (visited on 10/18/2019).
{: fs-2}
<sup>867</sup>Ricardian contracts; Dmitri Koteshov, Smart vs. Ricardian Contracts; Grigg, "The Ricardian contract"; What is a Ricardian Contract?
{: fs-2}
<sup>868</sup>Accord Project. url: https://www.accordproject.org/ (visited on 10/18/2019); Overview | OpenLaw Docs. url: https://docs.openlaw.io/ (visited on 10/18/2019); Clause Inc. url: https://clause.io/ (visited on 10/18/2019).
{: fs-2}
<sup>869</sup>Accord Project.
{: fs-2}
<sup>870</sup>Ricardian contracts.
{: fs-2}
<sup>871</sup>Daniel Zhang. DocuSign and Blockchain. en. Text. June 2018. url:  https://www.docusign.com/products/blockchain (visited on 10/18/2019).
{: fs-2}
<sup>872</sup>Zhang, DocuSign and Blockchain.
{: fs-2}
<sup>873</sup>Ibid.
{: fs-2}
***

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-1/">Introduction</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-2/">Part I)Background Research &gt; 1)Literature Review &gt; 1.1) Scoping Review</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-3/">1.2 Research Questions</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-4/">1.3 Report Structure</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-5/">1.4 Research Methodology</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-6/">1.5 Music Business Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-7/">1.6 Legal Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-8/">1.7 Automation Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-9/">1.8 Value Web Perspective</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-20/">2) Music Industry Supply Chain and Work Registration Standards</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-30/">3) Legal Frameworks Primer</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-40/">4) Music Licensing Primer</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-50/">5) Technology Primer</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-60/">Part II) Ricardian Contract &gt; 6) Motivation</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-70/">7) Decentralized Media Platforms</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-80/">8) Methods</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-90/">9) Discussion</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-100/">Conclusion</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-110/">References</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/blockchain-mediated-licensing-120/">Appendix</a></li></ul>

***

</div>

---
layout: default
title: II. THE INGENUITY AND LIMITATIONS OF BITCOIN 
parent: § Crypto and Blockchain Fundamentals 
grand_parent: Cryptocurrency 
nav_order: 20 
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

## II. THE INGENUITY AND LIMITATIONS OF BITCOIN
*“Bitcoin[] is a remarkable cryptographic achievement [and] the ability to create something which is not duplicable in the digital world has enormous value.”* – Eric Schmidt, former CEO of Google<sup>23</sup>

*“I think the fact that within the Bitcoin universe an algorithm replaces the functions of [the government] . . . is actually pretty cool. I am a big fan of Bitcoin.”* – Al Gore, 45th Vice President of the United States<sup>24</sup>

Nakamoto’s nine-page white paper specified the technical requirements for the “Internet of Value.”<sup>25</sup> Quite simply, Nakamoto proposed “[a] purely peer-to-peer version of electronic cash [that] would allow online payments to be sent directly from one party to another without going through a financial institution.”<sup>26</sup> Bitcoin achieves this by shifting: (1) from government-issued currencies to a cryptocurrency; (2) from trusted third parties to automated and community-driven counterparty risk mitigation; and (3) from party-level record keeping to shared record keeping.

### 1. From government-issued currencies to a cryptocurrency:
Rather than use a government-issued currency, Bitcoin created a new *cryptocurrency*—a digital currency secured by cryptography that makes it nearly impossible to counterfeit.<sup>27</sup> It is not controlled by any government or institution. Rather, Bitcoin’s monetary policies are programmed into the software.<sup>28</sup>

***
<sup>23</sup>. IDG News Service, *Google’s Schmidt: Bitcoin Is a Remarkable Cryptographic Achievement*, YOUTUBE (Mar. 3, 2014), [https://perma.cc/59QE-4H67]. 
{: .fs-2}
<sup>24</sup>. Kyle Samani, *How Crypto Will Reshape Capitalism as We Know It*, FORBES (Oct. 4, 2017), [https://perma.cc/X83C-2MUT]. 
{: .fs-2}
<sup>25</sup>. *See generally* SATOSHI NAKAMOTO, BITCOIN: A PEER-TO-PEER ELECTRONIC CASH SYSTEM (2008),[https://perma.cc/TL4X-DAY7]; *see also The Internet of Value: What It Means and How It Benefits Everyone*, RIPPLE (June 21, 2017), [https://perma.cc/R4TT6V7E]. 
{: .fs-2}
<sup>26</sup>. NAKAMOTO, *supra* note 25, at 1. 
{: .fs-2}
<sup>27</sup>. Cryptography is “a method of protecting information and communications through the use of codes so that only those for whom the information is intended can read and process it.” Margaret Rouse, *Cryptography,* TECH TARGET, [https://perma.cc/P59E-EJF3] (last visited Mar. 4, 2020). 
{: .fs-2}
<sup>28</sup>. See Nakamoto, *supra* note 25, at 1-3.
{: .fs-2}
***

Specifically, Bitcoin’s software capped the total monetary supply at 21 million bitcoins and has an automatic monetary distribution schedule.<sup>29</sup> The last bitcoin will be released in the year 2140.<sup>30</sup>

### 2. From TTPs to automation and community-driven counter-party risk mitigation:
Rather than rely on TTPs to mitigate counter-party risks, Bitcoin automates some of the services normally done by TTPs and engages a community to perform other services.<sup>31</sup> For an automation example, Bitcoin (and many blockchain applications that followed) relies on cryptographic private-public key pairs to verify account ownership.<sup>32</sup> Whoever is in possession of the private key is assumed to be the legitimate owner of the account.<sup>33</sup> Validating transactions to prevent double spending is a bit trickier to solve without trusted third parties. Senders cannot be trusted to verify that they have enough cryptocurrency in their accounts to fund their transactions. An independent verifier is needed, but Nakamoto did not want to rely on traditional financial institutions to provide the validation.<sup>34</sup> Here was Nakamoto’s brilliant solution: reward other people in the network (called “miners”)<sup>35</sup> with newly issued bitcoins to validate all the recently submitted

***
<sup>29</sup>. Paul Vigna et al., *Why Bitcoin? Why Now?*, WALL ST. J. (Dec. 9, 2017), [https://perma.cc/T4FK-S8UH]. 
{: .fs-2}
<sup>30</sup>. *Id.* 
{: .fs-2}
<sup>31</sup>. *See* Nathan Reiff, *Blockchain Won’t Cut Out Intermediaries After All,* INVESTOPEDIA (Mar. 5, 2020), [https://perma.cc/Y3CP-9BGB]. 
{: .fs-2}
<sup>32</sup>. *See* Demiro Massessi, *Blockchain Public/Private Key Cryptography in a Nutshell,* MEDIUM (Mar. 5, 2020), [https://perma.cc/S42R-VGRS]. 
{: .fs-2}
<sup>33</sup>. *See* Evan S. Strassberg & Brad R. Jacobsen, *Regulation of the Unregulated: How Bitcoin and Cryptocurrencies Show That the Government Can Regulate Anything,* 24 WESTLAW J. 6, 6 (2018). 
{: .fs-2}
<sup>34</sup>. *See* NAKAMOTO, *supra* note 25, at 1. 
{: .fs-2}
<sup>35</sup>. The Bitcoin protocol is based on a gold mining metaphor. Just as gold miners work using physical resources to excavate gold from gold mines, Bitcoin miners work using computer resources to release new bitcoins; Bitcoin, like gold, has a limited supply, making it a rare commodity. *See* Danton Bryans, *Bitcoin and Money Laundering: Mining for an Effective Solution,* 89 IND. LAW J. 441, 446 (2014); Benjamin Akins et al., *The Case for the Regulation of Bitcoin Mining as a Security,* 19 VA. J. L. & TECH. 669, 677-78 (2015). Just as it gets harder to mine gold as a gold mine is depleted, Bitcoin releases fewer new digital coins over time. See Adam Barone, *What Happens to Bitcoin After All 21 Million Are Mined?*, INVESTOPEDIA (Oct. 22, 2019), [https://perma.cc/TYP4-CX2A].
{: .fs-2}
***

transactions.<sup>36</sup> The economic incentives of the Bitcoin network motivate validators to play by the rules.<sup>37</sup>

### 3. From party-level record keeping to shared recordkeeping:
The Bitcoin network maintains a digital ledger, called a blockchain, <sup>38</sup> to serve as the universal record of truth. The ledger is distributed to all the host computers (called “nodes”)<sup>39</sup> that run the Bitcoin network. There were over 9,000 Bitcoin nodes as of December 2019.<sup>40</sup>

Overall, Bitcoin promises to deliver the following benefits:

***
<sup>36</sup>. Bryans, *supra* note 35, at 446; Akins, *supra* note 35, at 678-79. 
{: .fs-2}
<sup>37</sup>. Nakamoto wrote this about the economic incentives to motivative miners to behave honestly: If a greedy attacker is able to assemble more CPU power than all the honest nodes, he would have to choose between using it to defraud people by stealing back his payments, or using it to generate new coins. He ought to find it more profitable to play by the rules, such rules that favour him with more new coins than everyone else combined, than to undermine the system and the validity of his own wealth. NAKAMOTO, *supra* note 25, at 4. 
{: .fs-2}
<sup>38</sup>. The term “blockchain” is used several ways. Sometimes the term refers broadly to an entire “blockchain application.” For example, people call the entire Bitcoin network a “blockchain.” *See* Nathan Reiff, *Blockchain Explained*, INVESTOPEDIA (Feb. 1, 2020), [https://perma.cc/4BBW-VPKM]. The term can also be used to describe the structure of the digital ledger within an application. *Id.* With a blockchain structure, newly submitted transactions are sequenced and collected into a block (see Figure below). I*d.* The block comprises a header and a payload of transactions. See Le Su et al., *Securing Intelligent Transportation System: A Blockchain-Based Approach with Attack Mitigation,* in SMART BLOCKCHAIN (Meikang Qiu ed., Springer Nature Switz. 2019). The block header includes a pointer to the previous block of transactions, forming a chain of sequenced blocks over time, all the way back to the first block, called the “genesis block.” *See id; see also* Carla Tardi, *Genesis Block*, INVESTOPEDIA (Sept. 11, 2019), [https://perma.cc/48UG-N3MP]. 
{: .fs-2}
**Distributed Ledger Structured as a Chain of Blocks**
{: .fs-2}

![Distributed Ledger Structured as a Chain of Blocks](https://statics.bsafes.com/images/papers/crypto-and-blockchain-fundamentals-fig-0.png)

<sup>39</sup>. Each Bitcoin node is a host computer that runs the Bitcoin software and keeps a copy of the digital ledger; each node within the network has a unique identifier called an Internet Protocol (IP) address. *See *LACITY, *supra* note 14, at 227. 
{: .fs-2}
<sup>40</sup>. The actual number of Bitcoin nodes is difficult to track because some nodes operate behind firewalls. *See* David Hundeyin, *Number of Reachable Bitcoin Nodes Fell 19% in 2018,* CCN.COM (Dec. 13, 2018), [https://perma.cc/W3LE-CM52]. This site tracks “reachable” nodes: *Global Bitcoin Nodes Distribution,* BITNODES, (Mar. 19, 2020), [https://perma.cc/5JYT-XDXE].
{: .fs-2}
***

- **No need for reconciliations.** Bitcoin’s blockchain has one distributed ledger that is copied on every node, serving as one version of the truth.<sup>41</sup> Once transactions are added to the ledger, they are never deleted or modified, a property known as immutability. <sup>42</sup> The process for updating the ledger works as follows: New transactions submitted to the Bitcoin network are verified or rejected by miners’ computers competing to create the next block of transactions.<sup>43</sup> Verified transactions are timestamped, sequenced, secured with unique cryptographic identifiers, and appended to the ledger.<sup>44</sup> The first miner that updates the ledger distributes the update to the other nodes in the Bitcoin network.<sup>45</sup> Once the nodes accept the update, the network reaches *consensus,* meaning that they all agree, this is the “record of truth.”<sup>46</sup>

- **Anonymity.** Bitcoin’s blockchain allows two parties to exchange value in anonymity.<sup>47</sup> The public ledger records payments from and to Bitcoin accounts (called “addresses”), but no personal information is tracked or stored.<sup>48</sup> Anyone with access to the Internet can view the entire blockchain.<sup>49</sup>

- **Predictable and lower transaction fees.** Bitcoin’s blockchain was designed to require very low transaction fees from trading partners.<sup>50</sup> People sending bitcoins from an address

***
<sup>41</sup>. *See* LACITY, *supra* note 14, at 45. 
{: .fs-2}
<sup>42</sup>. *See id.* at 221. 
{: .fs-2}
<sup>43</sup>. *See* Brandon Ferrick, *Modernizing the Stockholder Shield: How Blockchains and Distributed Ledgers Could Rescue the Appraisal Remedy,* 60 B.C. L. REV. 621, 652-53 (2019). 
{: .fs-2}
<sup>44</sup>. *See* LACITY, *supra* note 14, at 213. 
{: .fs-2}
<sup>45</sup>. *See id.* at  47. 
{: .fs-2}
<sup>46</sup>. *See* MICHAEL J. CASEY & PAUL VIGNA, THE TRUTH MACHINE: THE BLOCKCHAIN AND THE FUTURE OF EVERYTHING 64-65 (2018); NAKAMOTO, *supra* note 25, at 3; Consensus, BITCOIN, [https://perma.cc/DK6J-AA3T] (last visited Feb. 26, 2020). 
{: .fs-2}
<sup>47</sup>. *See* Matthew Kien-Meng Ly, Coining Bitcoin’s “Legal-Bits”: *Examining the Regulatory Framework for Bitcoin and Virtual Currencies,* 27 HARV.J. L. & TECH. 587, 593 (2014). 
{: .fs-2}
<sup>48</sup>. *Id. *
{: .fs-2}
<sup>49</sup>. *See Block Explorer*, BLOCKCHAIN.COM, [https://perma.cc/X7PQ-S9F4] (last visited Feb. 27, 2020). 
{: .fs-2}
<sup>50</sup>. *See* NAKAMOTO, *supra* note 25, at 4; Jonathan B. Turpin, *Bitcoin: The Economic Case for a Global, Virtual Currency Operating in an Unexplored Legal Framework,* 21 IND. J. GLOBAL LEGAL STUD. 335, 336 (2014). Miners are primarily incentivized to verify and
{: .fs-2}
***

are supposed to offer a small fee to incentivize miners to verify their transactions, but an additional purpose of the fees is to prevent Denial of Service (DoS) attacks.<sup>51</sup> Planning ahead, Nakamoto also realized that once there were enough bitcoins in circulation, transaction fees could become the sole miner incentive.<sup>52</sup>

Figure 1: An Example of a Transaction Stored on Bitcoin’s Public Ledger

![Figure 1: An Example of a Transaction Stored on Bitcoin’s Public Ledger](https://statics.bsafes.com/images/papers/crypto-and-blockchain-fundamentals-fig-1.png)

***This transaction, which occurred on February 25, 2016, shows a transfer of value from the sender’s address on the right to the receiver’s address on the left. The sender also provided a small transaction fee for the miner of .005 bitcoins. The “hash” is a unique transaction identifier calculated from the inputs.***

***
add transactions to the blockchain by winning a block reward of newly released bitcoins. Turpin, *supra*, at 340-41. The initial mining reward was 50 bitcoins per block, with the reward being halved every 210,000 blocks. Rainer Böhme et al., *Bitcoin: Economics, Technology, and Governance*, 29 J. ECON. PERSP. 213, 218 (2015); Christine Kim, *With 18 Million Bitcoins Mined, How Hard Is That 21 Million Limit?,* COINDESK, [https://perma.cc/UP2G-9DZT] (last updated Oct. 21, 2019). This website tracks the current mining reward (which was 12.5 bitcoins per block in January 2020): Bitcoin Block *Reward Halving Countdown,* [https://perma.cc/GU7S-C5WG] (last visited Feb. 27, 2020). 
{: .fs-2}
<sup>51</sup>. *See* NAKAMOTO,*supra* note 25, at 4; Böhme et al., *supra* note 50, at 218. A Denial of Service (DoS) attack is a type of malicious attack that floods a network with so many transactions that it disrupts service for legitimate users. Böhme et al., supra note 50, at 228; Marcel T. Rosner & Andrew Kang, *Understanding and Regulating Twenty-First Century Payment Systems: The Ripple Case Study,* 114 MICH. L. REV. 649, 659 (2016). By requiring a small transaction fee, a malicious actor would soon find it too expensive to flood the Bitcoin network with millions of phony transactions. *See* NAKAMOTO, *supra* note 25, at 4. 
{: .fs-2}
<sup>52</sup>. NAKAMOTO, *supra *note 25, at 4.
{: .fs-2}
***

- **Financial Inclusion.** Bitcoin provides a way for lower income people to transfer value without owning a checking account or relying on expensive money transmitters.<sup>53</sup>

- **Rapid settlement times compared to TTPs.** Bitcoin’s blockchain is designed to create a new block of recent transactions—on average, every ten minutes.<sup>54</sup>

- **Democratic and predictable changes in the rules.** Bitcoin’s blockchain provides a non-fiat, universal cryptocurrency guided by an open community.<sup>55</sup> Anyone can propose ideas to improve Bitcoin by submitting a Bitcoin Improvement Proposal (BIP).<sup>56</sup> The whole Bitcoin community (miners, developers, and users) can vote on the proposal based on its merit.<sup>57</sup>

- **Heightened security.** The nodes in the Bitcoin network constantly chatter with each other to make sure no party tampers with the records after-the-fact.<sup>58</sup> If anyone cheats, the other parties’ nodes automatically ignore it.<sup>59</sup> An attacker would need to commandeer over fifty percent of the network and try to rewrite history before any of the other nodes noticed.<sup>60</sup> Additionally, anyone who could take over fifty percent of the network would devalue his or her own fortune.<sup>61</sup> Thus, Nakamoto

***
<sup>53</sup>. DAVID ORRELL & ROMAN CHLUPATÝ, THE EVOLUTION OF MONEY 201-02 (2016). 
{: .fs-2}
<sup>54</sup>. *Id.* at 200; Böhme et al., *supra* note 50, at 217. 
{: .fs-2}
<sup>55</sup>. *See* Kien-Meng Ly, *supra* note 47, at 589-90; Lawrence J. Trautman & Alvin C. Harrell, *Bitcoin Versus Regulated Payment Systems: What Gives?,* 38 CARDOZO L. REV. 1041, 1066 (2017); Alice Lynx, *Is Bitcoin a Fiat Currency? Why? or Why Not?,* CRYPTALKER, [https://perma.cc/54JP-6FFV] (last visited Feb. 28, 2020). 
{: .fs-2}
<sup>56</sup>. Kevin Werbach, *Trust, but Verify: Why the Blockchain Needs the Law,* 33 BERKELEY TECH. L.J. 487, 548 (2018); Harsh Agrawal, *What Is a BIP (Bitcoin Improvement Proposal)? Why Do You Need to Know About It?,* COINSUTRA, [https://perma.cc/6SR2- U7WJ] (last updated Sept. 6, 2019). 
{: .fs-2}
<sup>57</sup>. Agrawal, *supra* note 56. As of this writing, 342 BIPs have been submitted, of which 37 have been finalized. *Bitmark Improvement Process,* GITHUB, [https://perma.cc/CM75-24WR] (last visited Feb. 28, 2020). 
{: .fs-2}
<sup>58</sup> *See* NAKAMOTO, *supra* note 25, at 3, 5; Chris Grundy, *How to Run a Full Node,* THE COIN OFFERING (Sept. 13, 2018), [https://perma.cc/2HAE-NST9]; Jameson Lopp, *Bitcoin’s Security Model: A Deep Dive,* COINDESK, [https://perma.cc/8GJB-MTK5] (last updated Feb. 22, 2019). 
{: .fs-2}
<sup>59</sup>. *See* NAKAMOTO, *supra* note 25, at 6. 
{: .fs-2}
<sup>60</sup>. PRIMAVERA DE FILIPPI & AARON WRIGHT, BLOCKCHAIN AND THE LAW: THE RULE OF CODE 25 (Harvard Univ. Press 2018); Lopp, *supra* note 59. 
{: .fs-2}
<sup>61</sup>. *See* DE FILIPPI & WRIGHT, *supra* note 61, at 25.
{: .fs-2}
***

designed the protocol to be computationally and financially impractical for an attack. Thus far, there has been only one major attack on the Bitcoin network, which occurred back in 2010.<sup>62</sup> Nakamoto quickly remedied the software vulnerability.<sup>63</sup> (Most heists of bitcoins and other cryptocurrencies happen at the vulnerable access points of digital wallets where private keys are stored, not on the ledger itself.)<sup>64</sup>

Bitcoin is the most visible on-going, live experiment for an open, public, secure, non-governmental, non-TTP reliant “Internet of Value.” All are welcome to participate. Millions of people use it—over 32 million Bitcoin wallets have been created.<sup>65</sup> Thousands of people help secure it by being miners. Bitcoin proves that the “Internet of Value” is technically feasible and that a shared digital ledger is highly secure. However, Bitcoin—like all innovations—has advantages and disadvantages. Bitcoin’s limitations include: 

- **Low transactions per second (TPS).** Bitcoin’s network processes about two to six TPS.<sup>66</sup> By comparison, Visa and Mastercard can process thousands of TPS.<sup>67</sup> 

- **Slower settlement times than other blockchains.** While Bitcoin has faster settlement times than traditional TTPs, Bitcoin is one of the slowest blockchain networks.

***
<sup>62</sup>. LACITY, *supra* note 14, at 138. 
{: .fs-2}
<sup>63</sup>. “The Bitcoin blockchain was hacked in August 2010 when someone exploited a software vulnerability to create 184 *billion* bitcoins, a highly suspicious act given the maximum money supply is only 21 *million* bitcoins.” *Id.* (emphasis added). “Nakamoto quickly hard forked the blockchain to remove the [184 plus] billion [b]itcoins.” Charlie Shrem, *Bitcoin’s Biggest Hack in History: 184.4 Billion Bitcoin from Thin Air,* HACKERNOON (Jan. 11, 2019), [https://perma.cc/WP7V-HZL5]. 
{: .fs-2}
<sup>64</sup>. Henry S. Zaytoun, *Cyber Pickpockets: Blockchain, Cryptocurrency, and the Law of Theft, *97 N.C. L. REV. 395, 407-08 (2019). 
{: .fs-2}
<sup>65</sup>. Alex Lielacher, *How Many People Use Bitcoin in 2020?*, BITCOIN MKT.J. (Feb. 5, 2020), [https://perma.cc/824U-SLZ7]. 
{: .fs-2}
<sup>66</sup>. *See Transaction Rate,* BLOCKCHAIN, [https://perma.cc/4KAK-M95P] (last visited Mar. 26, 2020). 
{: .fs-2}
<sup>67</sup>. Ryan Vlastelica, *Why Bitcoin Won’t Displace Visa or Mastercard Soon,* MARKETWATCH (Dec. 18, 2017), [https://perma.cc/U6MV-GVA5].
{: .fs-2}
***

Transactions are not considered to be truly settled for at least an hour. <sup>68</sup> 

• **Threats to anonymity.** Although Bitcoin transactions are anonymous in that no personal identities are revealed on the public ledger, meta patterns can emerge where identities could be deduced.<sup>69</sup> People thus consider Bitcoin to be “pseudonymous” rather than “anonymous.”<sup>70</sup> 

• **Traditional enterprises need confidentiality, not anonymity.** Traditional enterprises need information about their transactions to be visible, but only to authorized parties. Most enterprises do not see use cases for public blockchains like Bitcoin. 

• **Poor store of value.** Compared to fiat currencies, Bitcoin’s price volatility is high.<sup>71</sup> In 2019, Bitcoin’s price ranged from $3,400 to over $12,600 per bitcoin.<sup>72</sup> 

• **Poor user access and experience.** Users connect directly to the Bitcoin network by using a digital

***
<sup>68</sup>. Although a new block is created every ten minutes on average, the actual settlement time is longer due to the possibility of a temporary divergence of the network. *See* Joseph Bonneau, *How Long Does It Take for a Bitcoin Transaction to be Confirmed?,* COIN CENTER (Nov. 3, 2015), [https://perma.cc/78H9-3A4T]. Sometimes two nodes in a distributed blockchain network create the next block at the same time, resulting in two versions of the top of the ledger called a “soft fork.” *See id.*; John Light, *The Differences Between a Hard Fork, a Soft Fork, and a Chain Split, and What They Mean for the Future of Bitcoin*, MEDIUM (Sept. 25, 2017), [https://perma.cc/MRB2-Z5CQ]. For a short while, different nodes in the network work off of different branches of the ledger until one branch is established as the longest and therefore the valid branch. *See id.* To confidently consider a bitcoin transaction to be settled, it is generally recommended to wait until the transaction is six blocks deep, which takes an hour on average. *See* Bonneau, *supra*. 
{: .fs-2}
<sup>69</sup>. LACITY, *supra* note 14, at 148. For example, if two parties to an exchange know each other’s identities, each can trace subsequent transactions in or out of those addresses. *See id.* Moreover, “[m]any transactions are funded with multiple addresses,” allowing a party to tie an identity to even more addresses. *Id. *
{: .fs-2}
<sup>70</sup>. *Bitcoin Anonymity-Is Bitcoin Anonymous?*, BUY BITCOIN WORLDWIDE, [https://perma.cc/2UPP-9HEW] (last visited Feb. 26, 2020). 
{: .fs-2}
<sup>71</sup>. Bitcoin’s price is more volatile than emerging fiat currencies, oil, gold, and U.S. stocks. *See Bitcoin Volatility vs Other Assets,* WOODBULL CHARTS, [https://perma.cc/F4RX-3QGN] (last visited Feb. 26, 2020). 
{: .fs-2}
<sup>72</sup>. *Bitcoin Price,* COINBASE, [https://perma.cc/QWW4-29YA] (last visited Feb. 26, 2020).
{: .fs-2}
***

wallet.<sup>73</sup> Few users are technically sophisticated enough to protect their wallets.<sup>74</sup>

• **High resource consumption. **To successfully compete for new bitcoins, Bitcoin miners use specialized computer hardware that consumes a lot of electricity.<sup>75</sup> 

• **Limited functionality.** Bitcoin is just a payment system to send and receive bitcoins. It cannot do much else. 

• **Regulatory uncertainty.** At first, regulators around the world ignored Bitcoin.<sup>76</sup> However, regulatory bodies have since responded, as discussed in this issue of *The Arkansas Law Review.* <sup>77</sup>

The blockchain innovations that followed Bitcoin aimed to improve upon Bitcoin’s limitations.

***

#### Table of Contents
{: .no_toc}
<ul><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-1/">I. FROM THE “INTERNET OF INFORMATION” TO THE “INTERNET OF VALUE”</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-2/">II. THE INGENUITY AND LIMITATIONS OF BITCOIN</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-3/">III. Beyond Bitcoin - Other Technical Innovations</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-4/">IV. BLOCKCHAIN-BASED APPLICATION EXAMPLES</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-5/">V. New Fundraising Models</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-6/">VI. WHY THE “INTERNET OF VALUE” NEEDS LEGAL PRACTITIONERS</a></li></ul>
</div>

</div>

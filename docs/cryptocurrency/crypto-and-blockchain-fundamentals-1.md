---
layout: default
title: I. FROM THE “INTERNET OF INFORMATION” TO THE “INTERNET OF VALUE”
parent: § Crypto and Blockchain Fundamentals 
grand_parent: Cryptocurrency 
nav_order: 10 
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

## I. FROM THE “INTERNET OF INFORMATION” TO THE “INTERNET OF VALUE”

*“I believe blockchain will do for trusted transactions what the Internet has done for information.”* — Ginni Rometty, CEO of IBM<sup>1</sup>

Since the 1990s, we have had an “Internet of Information” that allows us to seamlessly share information such as documents, images, emails, and videos over the Internet. While most Internet users do not need to understand the details of the technical protocols<sup>2</sup> operating underneath user-friendly software interfaces, it is helpful to understand how they work at a high-level. With the “Internet of Information,” *copies* of information are routed

***
<sup>1</sup> Ginni Rometty, CEO, IBM, Keynote Address at IBM InterConnect (Mar. 21, 2017), [https://perma.cc/M87K-WZGT]. 
{: .fs-2}
<sup>2</sup>. Transmission Control Protocol/Internet Protocol (TCP/IP) is the Internet’s primary protocol. *See* Jerry Kang, *Information Privacy in Cyberspace Transactions,* 50 STAN. L. REV. 1193, 1221 n.111 (1998). It breaks messages into packets and routes them to their destination as defined by a unique address called an “IP address.” *Id.* Every device connected to the Internet has a unique IP address, including computers, mobile phones, laptops, printers, IoT devices, servers, routers, etc. *Id.*
{: .fs-2}
***

over the Internet.<sup>3</sup> If a sender emails a friend, the sender keeps the original email, and the friend receives a copy of the email.<sup>4</sup> To transact *value*, i.e., money, over the Internet, one cannot send a copy. Instead, after the transfer of value is complete, the sender should no longer have the money, but rather the recipient should.

The best way to understand how blockchain technologies enable the “Internet of Value” is to compare them to the way trading partners transact today. Before adopting blockchain technologies, parties transact value over the Internet (and other networks) by: (1) using government-issued currencies as legal tender; (2) engaging trusted third parties (TTPs) to mitigate counter-party risks—the risk each trading party bears that the other party will not fulfill its contractual obligations; and (3) maintaining separate accounting systems to record transactions. Each of these transaction facilitators have the following advantages and disadvantages:

**Government-issued currencies:** Governments issue and regulate legal tender. The advantages of government-issued currencies are that they serve as legal mediums of exchange for the payment of debts, as common measures of value, and as stores of value that aim to retain their worth over time. The United Nations recognizes 180 currencies as legal tender.<sup>5</sup> On what some consider to be the downside, most sovereign currencies are now fiat, backed solely on the promises of governments.<sup>6</sup> Governments can print fiat money at will, causing inflation, and change regulations on a whim.<sup>7</sup> Governments can also freeze, seize, or restrict access to one’s assets.<sup>8</sup>

***
<sup>3</sup>. JEAN-HERVÉ LORENZI & MICKAËL BERREBI, PROGRESS OR FREEDOM: WHO GETS TO GOVERN SOCIETY’S ECONOMIC AND TECHNOLOGICAL FUTURE? 53 (Dina Leifer trans., 2019). 
{: .fs-2}
<sup>4</sup> *Id. *
{: .fs-2}
<sup>5</sup>. Benjamin Elisha Sawe, *How Many Currencies Exist in the World?,* WORLDATLAS (June 28, 2018), [https://perma.cc/SGJ9-JPZB]. 
{: .fs-2}
<sup>6</sup>. Trevor I. Kiviat, *Beyond Bitcoin: Issues in Regulating Blockchain Transactions*, 65 DUKE L.J. 569, 576 (2015). 
{: .fs-2}
<sup>7</sup>. Stephanie A. Lemchuk, *Virtual Whats?: Defining Virtual Currencies in the Face of Conflicting Regulatory Guidances,* 15 CARDOZO PUB. L. POL’Y & ETHICS J. 319, 320-21 n.6-7 (2017). 
{: .fs-2}
<sup>8</sup>. For example, the Greek banks would not allow account holders to withdraw more than 60 euros a day in 2015.
{: .fs-2}
***

**Trusted third parties:** When transferring value, “parties rely on [TTPs] to . . . mitigate counter-party risks.”<sup>9</sup> Banks, credit card companies, money transmitters, notaries, and other TTPs “provide independent ‘truth attestations’ such as notarizing signatures; verifying identity; verifying ownership; authenticating assets;” assuring accounts are funded before value is transferred to prevent double spending; and “attesting that agreements have been properly executed.”<sup>10</sup> TTPs provide these and many other vital services to facilitate trade (the advantages), for which they earn significant transaction fees (a disadvantage).<sup>11</sup> Additionally, banks lose money on checking accounts and have few financial incentives to service low-income people.<sup>12</sup> Consequently, over a quarter of the world’s population does not have access to financial services.<sup>13</sup>

**Party-level record keeping:** Before a blockchain application, every party maintains its own accounting records.<sup>14</sup> Some advantages are that each party can swiftly and unilaterally execute decisions about accounting rules, transaction reversals, and software upgrades within the boundaries of the firm. However, with party-level record keeping, every party has its own version of the transaction that needs to be reconciled with trading partners, and reconciliations are expensive and time-consuming.<sup>15</sup> Once reconciled, there is nothing to prevent trading partners from

***
Associated Press, The Latest:* Strict Limits on Bank Withdrawals Will Not Apply to Foreign Credit Cards*, U.S. NEWS & WORLD REP. (June 28, 2015), [https://perma.cc/76BD-B34T]. 
{: .fs-2}
<sup>9</sup>. Mary Lacity et al., *Special Issue Editorial: Delivering Business Value Through Enterprise Blockchain Applications*, 18 MIS Q. EXECUTIVE ix, x (2019). 
{: .fs-2}
<sup>10</sup>. *Id*. 
{: .fs-2}
<sup>11</sup>. According to McKinsey & Company, the world sends more than $135 trillion across borders each year. MCKINSEY & CO., GLOBAL PAYMENTS 2016: STRONG FUNDAMENTALS DESPITE UNCERTAIN TIMES 2, 14 (2016), [https://perma.cc/9YT6-2JYN]. Third-party intermediaries collect about $2.2 trillion in revenue to facilitate these transactions. *Id*. at 2. 
{: .fs-2}
<sup>12</sup>. On average, American banks incurred costs of $349 a year per checking account and recovered only $268 in transaction fees. AM. BANKERS ASS’N, FEES AND PRICING OF BANKING PRODUCTS 108 (2016), [https://perma.cc/6VPZ-2F8B]. 
{: .fs-2}
<sup>13</sup>. ASLI DEMIRGÜÇ-KUNT ET AL., THE WORLD BANK GROUP, THE GLOBAL FINDEX DATABASE 2 (2017) (“. . . 69 percent of adults now have [a bank] account, up from 62 percent in 2014 and 51 percent in 2011.”). 
{: .fs-2}
<sup>14</sup>. MARY C. LACITY, A MANAGER’S GUIDE TO BLOCKCHAIN FOR BUSINESS: FROM KNOWING WHAT TO KNOWING HOW 42 (2018). 
{: .fs-2}
<sup>15</sup>. *Id. *at 42-43.
{: .fs-2}
***

modifying records after the fact.<sup>15</sup> Thus, partners cannot be confident that they are dealing with the same historical record of transactions through time.

Satoshi Nakamoto—a pseudonym used by an unknown person or persons who remains anonymous to this day—imagined a world where people could safely, securely, and anonymously transfer value directly with each other (1) without using government-issued currencies, (2) without relying upon trusted third parties, and (3) without the need to reconcile records across trading partners.<sup>17</sup> Nakamoto’s innovation is Bitcoin, described in a white paper posted to a cryptographic mailing list on October 31, 2008.<sup>18</sup> The timing of Bitcoin was no accident. After the 2008 Global Financial Crisis—possibly the greatest economic disruption since the Great Depression of 1929—people became increasingly distrustful of financial institutions.<sup>19</sup> Movements like Occupy Wall Street ranted against wealth inequality and the influence of large financial institutions on government policy.<sup>20</sup> People rallied against the government’s power to control money.<sup>21</sup> Bitcoin has its roots in Libertarian and Cypherpunk values, which aim to create social and political change by circumventing governments and large financial institutions through privacyenhancing technologies.<sup>22</sup>

***
<sup>16</sup>. Id. at 43; see also Angela Walch, *The Path of the Blockchain Lexicon (and the Law),* 36 REV. BANKING & FIN. L. 713, 736-37 (2017). 
{: .fs-2}
<sup>17</sup>. See Deniz Appelbaum & Sean Stein Smith, *Blockchain Basics and Hands-on Guidance, Taking the Next Step Toward Implementation and Adoption,* THE CPA J. (June 2018), [https://perma.cc/9DFC-SLF6]. 
{: .fs-2}
<sup>18</sup>. Paul Vigna, *Bitcoin Turns 10: Still Not All Grown Up*, WALL ST.J., (Oct. 31, 2018), [https://perma.cc/SMX6-34NT]. 
{: .fs-2}
<sup>19</sup>. David De Cremer, *Why Our Trust in Banks Hasn’t Been Restored*, HARV. BUS. REV. (Mar. 3, 2015), [https://perma.cc/R9TS-CVV7]. 
{: .fs-2}
<sup>20</sup>. John L. Hammond, *The Anarchism of Occupy Wall Street*, 79 SCI. & SOC’Y 288, 288-89 (2015). 
{: .fs-2}
<sup>21</sup>. *See id. *
{: .fs-2}
<sup>22</sup>. LACITY, *supra* note 14, at 53-54; *see also* Nathaniel Popper, *Decoding the Enigma of Satoshi Nakamoto and the Birth of Bitcoin,* N.Y. TIMES (May 15, 2015), [https://perma.cc/D8ZA-DQ2C].
{: .fs-2}
***

***

#### Table of Contents
{: .no_toc}
<ul><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-1/">I. FROM THE “INTERNET OF INFORMATION” TO THE “INTERNET OF VALUE”</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-2/">II. THE INGENUITY AND LIMITATIONS OF BITCOIN</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-3/">III. Beyond Bitcoin - Other Technical Innovations</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-4/">IV. BLOCKCHAIN-BASED APPLICATION EXAMPLES</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-5/">V. New Fundraising Models</a></li><li> <a href="http://localhost:4000/docs/cryptocurrency/crypto-and-blockchain-fundamentals-6/">VI. WHY THE “INTERNET OF VALUE” NEEDS LEGAL PRACTITIONERS</a></li></ul>
</div>

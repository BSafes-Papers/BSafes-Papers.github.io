---
layout: default
title: III. Beyond Bitcoin - Other Technical Innovations 
parent: § Crypto and Blockchain Fundamentals 
grand_parent: Cryptocurrency 
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
## III. Beyond Bitcoin: Other Technical Innovations
*“I think that there is effective forward motion in the resolution and the ability to address some of the technical challenges that exist.”* — Eamonn Maguire, Global Lead, Digital Ledger Services, KPMG<sup>78</sup>

Following Bitcoin’s launch in 2009, a proliferation of blockchain innovations emerged. Some notable examples are plotted on a timeline in Figure 2, listed in Table 1, and described below.

***
<sup>73</sup>. *Some Bitcoin Words You Might Hear*, BITCOIN, [https://perma.cc/E536-24G7] (last visited Feb. 26, 2020). 
{: .fs-2}
<sup>74</sup>. A digital wallet stores the private keys that controls Bitcoin accounts (addresses). LACITY, *supra* note 14, at 217. If the private key is lost or stolen, there is no way to recover the private keys. Id. 
{: .fs-2}
<sup>75</sup>. Digiconomist, a site that tracks Bitcoin’s energy consumption, reports that a single Bitcoin transaction consumes enough electrical energy to power an average U.S. household for twenty-two days. *Bitcoin Energy Consumption Index Chart,* DIGICONOMIST, [https://perma.cc/99AZ-K737] (last visited Feb. 26, 2020). 
{: .fs-2}
<sup>76</sup>. *See* LACITY, *supra* note 14, at 32-33. 
{: .fs-2}
<sup>77</sup>. *See generally* Carol Goforth, *The Case for Preempting State Money Transmission Laws for Crypto-Based Businesses*, 73 ARK. L. REV. 301 (2020). 
{: .fs-2}
<sup>78</sup>. Telephone Interview with Eamonn Maguire, Global Lead, Digital Ledger Services, KPMG (July 10, 2017).
{: .fs-2}
***
Figure 2: Timeline of Notable Blockchain Innovations

![Figure 2: Timeline of Notable Blockchain Innovations](https://statics.bsafes.com/images/papers/crypto-and-blockchain-fundamentals-fig-2.png)

Table 1: Blockchain Innovations Since Bitcoin

![Table 1: Blockchain Innovations Since Bitcoin](https://statics.bsafes.com/images/papers/crypto-and-blockchain-fundamentals-table-1.png)

### A. Cryptoassets 

- **Alternative coins. **After Bitcoin, many alternative cryptocurrencies called “altcoins” were created, aiming to improve upon Bitcoin’s protocol.<sup>79</sup> In 2011, the first altcoins— Namecoin and Litecoin—were created by copying and then modifying the Bitcoin codebase.<sup>80</sup> **Namecoin** aimed to extend Bitcoin’s functionality by storing more data in the transaction;<sup>81</sup> **Litecoin** aimed to speed settlement times by a factor of four.<sup>82</sup> By February 2020, there were more than 1,700 altcoins.<sup>83</sup>

***
<sup>79</sup>. *See* Larry D. Lahman, Bitcoins, *Blockchains and Satoshi Nakamoto,* 89 OKLA. B.J. 18, 19 (2018).
{: .fs-2}
***

- **Privacy coins.** Several cryptocurrencies aim to increase anonymity by using advanced cryptography such as ring signatures to mask senders’ addresses, stealth addresses to mask receivers’ addresses, and zero-knowledge proofs.<sup>84</sup> “These methods allow only the parties to a particular transaction to decipher data and to access funds stored on the blockchain even when posted on a public blockchain.”<sup>85</sup> For example, **Monero,** launched in 2014, is a cryptocurrency with increased data obfuscation compared to Bitcoin using ring signatures and stealth addresses.86 **Zcash** is another major privacy coin, launched in 2016.<sup>87sup> Designed by professors from Johns Hopkins, MIT, Technion, and Tel Aviv University, Zcash uses a cryptographic zero-knowledge proof which allows users to mask their addresses.<sup>88</sup>

***
<sup>80</sup>. James Frankenfield, *AltCoin,* INVESTOPEDIA, [https://perma.cc/C3LB-4J6R] (last updated Feb. 2, 2020). 
{: .fs-2}
<sup>81</sup>. NAMECOIN, [https://perma.cc/QMJ5-JHDZ] (last visited Mar. 7, 2020). 
{: .fs-2}
<sup>82</sup>. *About*, LITECOIN, [https://perma.cc/K2MA-ZZWE] (last visited Mar. 7, 2020). 
{: .fs-2}
<sup>83</sup>. Frankenfield, *supra* note 80. 
{: .fs-2}
<sup>84</sup>. *See* MARY LACITY ET AL., BLOCKCHAIN GOVERNANCE MODELS: INSIGHTS FOR ENTERPRISES 22, 45 (2019), [https://perma.cc/UPV9-KS5F]. *Zero[-]knowledge proofs* are a method for one party . . . to verify possession of a piece of information to other parties . . . without revealing the information. As a simple example, suppose Alice wants to prove to Bob that she knows the exact number of jellybeans that fills a large barrel without telling Bob the exact number. What might Alice do to convince Bob that she knows the amount? Alice could instruct Bob to take any number of jellybeans out of the barrel after she leaves the room. Bob makes his choice. Alice reenters the room and Bob exits the room. Alice recounts the beans and compares the current count with the previous count to calculate exactly how many jellybeans (if any) Bob removed. When Bob returns, Alice tells Bob exactly how many jellybeans he took. If Bob thinks Alice made a lucky guess, rounds of the same choice could be made over and over again. Eventually, Bob will be convinced that Alice possesses the knowledge of the exact number of jellybeans without ever revealing the number. In blockchain applications, zero-knowledge proofs are used to guarantee that transactions are valid without revealing information about the sender, receiver, and/or transaction. *Id.* at 46 (emphasis added). 
{: .fs-2}
<sup>85</sup>. *Id.* at 22. 
{: .fs-2}
<sup>86</sup>. *See Why Monero Is Different,* MONERO, [https://perma.cc/HN4N-ABB3] (last visited Mar. 8, 2020); *About Monero: A Brief History,* MONERO, [https://perma.cc/S2AC77WX] (last visited Mar. 8, 2020). Monero uses the CryptoNote protocol, developed by Nicolas van Saberhagen, that defines an algorithm with increased data obfuscation compared to Bitcoin. *See generally* NICOLAS VAN SABERHAGEN, CRYPTONOTE V 2.0 (2013), [https://perma.cc/P8NG-7YSS]. With Monero, a recipient’s address is only used once, so that the sender cannot trace subsequent transactions on the ledger. *Id*. at 6. When the recipient spends money out of that address (thus becoming a “sender” address in a subsequent transaction), the address gets hidden within a group signature. *Id.*
{: .fs-2}
***

- **Stablecoins.**Several cryptocurrencies aim to create a more stable store of value compared to Bitcoin by pegging the coin to a stable asset outside the network, such as pegging a digital coin to a fiat currency or to a commodity like gold.<sup>89</sup> Tether was the first stablecoin, launched in 2014, by a company called Tether Limited.<sup>90</sup> Buyers exchange one U.S. dollar for one tether coin, with Tether Limited allegedly storing each U.S. dollar in a bank reserve.<sup>91</sup> Crypto traders use tethers to take advantage of the price arbitrage across cryptocurrency exchanges.<sup>92</sup> They can buy cryptocurrencies at a lower price with tethers on one exchange without having to first withdraw fiat currency from another exchange.<sup>93</sup>

Other notable stablecoins pegged to fiat currencies have launched since Tether, including USD Coin and Gemini in 2018, JPM Coin in 2019, and the proposed Libra coin, to be launched in 2020. The **USD Coin**—created by Coinbase and Circle— launched the coin as part of a consortium, promising transparency over its U.S. dollar reserve management.<sup>94</sup> **Gemini** was founded

***
<sup>87</sup>. ZCASH, [https://perma.cc/MS4V-PB3Z] (last visited Mar. 8, 2020). 
{: .fs-2}
<sup>88</sup>. *Id.*
{: .fs-2}
<sup>89</sup>. BARRY EICHENGREEN, GLOBALIZING TITLE: A HISTORY OF THE INTERNATIONAL MONETARY SYSTEM 244 (3d ed. 2019). 
{: .fs-2}
<sup>90</sup>. *See* James Frankenfield, *Tether (USDT)*, INVESTOPEDIA, [https://perma.cc/A9ZE6TFW] (last updated June 25, 2020). 
{: .fs-2}
<sup>91</sup>. *About Us,* TETHER, [https://perma.cc/RA7F-9FZN] (last visited Mar. 8, 2020). Tether Limited promised that at any time, a buyer could get its U.S. dollar back and the coin would be destroyed. *See* Paul Vigna, *Large Bitcoin Player Manipulated Price Sharply Higher, Study Says*, WALL ST. J. (Nov. 4, 2019), [https://perma.cc/4T38-RNZH]. In 2017, however, the company could not meet withdrawal demands and stands accused of currency manipulation and fraud. Id. It has never provided a legal audit, despite many promises to do so. *Id*. Despite the risks, nearly 75 percent of all bitcoin trades were facilitated by Tether in 2019. *Id*. 
{: .fs-2}
<sup>92</sup>. *Tether Day Trading 2020,* DAY TRADING, [https://perma.cc/JZ52-L53Q] (last visited Mar. 6, 2020). 
{: .fs-2}
<sup>93</sup>. *See id.* 
{: .fs-2}
<sup>94</sup>. Coinbase, *Coinbase and Circle Announce the Launch of USDC – a Digital Dollar,* MEDIUM: THE COINBASE BLOG (Oct. 23, 2018), [https://perma.cc/JG6N-NA8N].
{: .fs-2}
***

by Cameron and Tyler Winklevoss.<sup>95</sup> The Gemini coin is another 1-to-1 peg with the U.S. dollar.<sup>96</sup> JP Morgan uses its **JPM Coin** to facilitate institution-to-institution transfers.<sup>97</sup> It is also pegged to the U.S. dollar.<sup>98</sup> **Libra**, the new token proposed by Facebook, will be pegged to a basket of fiat currencies (or perhaps to a local currency)<sup>99</sup> and will be managed by the Libra Association, a nonprofit membership organization based in Switzerland.<sup>100</sup> The U.S. Congress has fiercely questioned Facebook founder Mark Zuckerberg and Facebook’s Head of Calibra, David Marcus, over Libra.<sup>101</sup>

Besides pegging to fiat currencies, some stablecoins are pegged to commodities (e.g., **DGX** pegs one coin to one gram of gold)<sup>102</sup> or to other cryptocurrencies (e.g., **Dai**, launched in 2017, is pegged to the U.S. dollar but is also backed by **ether**, Ethereum’s cryptocurrency).<sup>103</sup> In the future, some cryptocurrencies may use algorithms to maintain a stable base price by automatically adjusting supply and demand.

- **Crypto-tokens.** A cryptocurrency is one type of cryptoasset, one that aims to function as digital money.<sup>104</sup> Other cryptoassets are *digital tokens* that represent other types of assets besides money.<sup>105</sup> Crypto-tokens can be used to represent *fungible* (non-unique) assets, such as loyalty rewards and airline frequent flyer miles, in which one token is interchangeable with another.<sup>106</sup> Crypto-tokens can also be used to represent *nonfungible* (unique) assets, where the token represents a particular asset in the real world, creating what one may consider to be the digital twin.<sup>107</sup> For example, a unique token could be created to represent a particular diamond, a particular medical device, a particular plot of land, or a particular work of art. Crypto-tokens create new ways to track assets through supply chains (discussed below).

***
<sup>95</sup>. Dante Alighieri Disparte, *Gemini: The Winklevoss Twins Break New Ground on Digital Trust,* FORBES (Jan. 29, 2019), [https://perma.cc/6FSM-VKXA]. 
{: .fs-2}
<sup>96</sup>. Jack Mathis, *Gemini’s New USD Cryptocurrency Stablecoin: A Whitepaper Deep Dive,* CCN.COM (Sept. 12, 2018), [https://perma.cc/Y3KH-X53S]. 
{: .fs-2}
<sup>97</sup>. Jesse Damiani, *JPMorgan Announces ‘JPM Coin,’ a USD-Pegged Cryptocoin for Cross-Border Payments, Security, and More*, FORBES (Feb. 14, 2019), [https://perma.cc/7Y7B-W6J9]. 
{: .fs-2}
<sup>98</sup> *Id.* 
{: .fs-2}
<sup>99</sup>. Jonathan Shieber, *In a Big Reversal, Libra Reportedly Could Peg Its Cryptocurrencies to National Currencies*, TECHCRUNCH (Oct. 20, 2019), [https://perma.cc/SU8R-R46G]. 
{: .fs-2}
<sup>100</sup>. CleanApp, *Who Owns the Libra Association?*, MEDIUM: CRYPTO L. REV. (Oct. 24, 2019), [https://perma.cc/ZNZ8-3EH8]. 
{: .fs-2}
<sup>101</sup>. *Id.*; Charlie Wood, *Facebook’s Blockchain Boss David Marcus Defends the Feasibility of Libra After a Quarter of Its Partners Drop Out,* BUS. INSIDER (Oct. 16, 2019), [https://perma.cc/3NZ6-8AFW]. 
{: .fs-2}
<sup>102</sup>. Lucent Exchange, *Gold-Backed Cryptocurrencies: Everything You Need to Know,* MEDIUM: CRYPTODIGEST (Sept. 12, 2019), [https://perma.cc/R7J5-LVPN]. 
{: .fs-2}
<sup>103</sup>. Tom Wilson, *Crypto Backed by Crypto: Dai Seeks to Change ‘Stablecoin’ Game,* REUTERS (Nov. 18, 2019), [https://perma.cc/G4TD-CPF4]. 
{: .fs-2}
<sup>104</sup>. Adam Haeems, *What Is a Crypto-Asset?*, MEDIUM: BABB (Apr. 27, 2018), [https://perma.cc/2UFM-R7UK].
{: .fs-2}
***

### B. Cryptocurrency Exchanges
Initially, the only way to interact with the Bitcoin network was to become a miner or to manage one’s own digital wallet, which requires significant technical skills. Many people saw the need for an exchange where users could easily buy and sell bitcoins with fiat currency. The first bitcoin exchange was **Bitcoin Market,** launched in March 2010 by a Bitcoin Talk member using the pseudonym “dwdollar.”<sup>108</sup> Jed McCaleb (born in Little Rock, Arkansas) soon after launched the most famous bitcoin exchange called **Mt. Gox **in 2010.1<sup>109</sup> McCaleb sold the site to Mark Karpelès in 2011.<sup>110</sup> Early exchanges operated under

***
<sup>105</sup>. **Tokenization vs. Encryption.** While encryption uses public-private key pairs to protect data, tokenization uses a token to protect data. *Tokenization vs. Encryption: Which One Is Better for Your Business?,* TOKENEX (July 19, 2013), [https://perma.cc/J4LF-3ANY] [hereinafter *Tokenization vs. Encryption*]. Specifically, “[t]okenization is the process of protecting sensitive data by replacing it with an algorithmically generated number called a token.”* Tokenization Explained,* PARIVARTHAN (Jan. 13, 2019), [**https://perma.cc/7TKKDPLH**]. To access the original data, an encryption solution decodes the encrypted data with a private key, whereas a tokenization solution exchanges the token for the sensitive data. *Tokenization vs. Encryption, supra. *
{: .fs-2}
<sup>106</sup>. Jake Frankenfield, *Crypto Tokens*, INVESTOPEDIA, [https://perma.cc/MN35- PW46] (last updated Apr. 3, 2018). 
{: .fs-2}
<sup>107</sup>. Carol R. Goforth, *How Blockchain Could Increase the Need for and Availability of Contractual Ordering for Companies and Their Investors,* 94 N.D. L. REV. 1, 10 n.41 (2019). 
{: .fs-2}
<sup>108</sup>. Nathaniel Whittemore & Clay Collins, *A History Of Crypto Exchanges: A Look At Our Industry’s Most Powerful Institutions,* NOMICS (Nov. 14, 2019), [https://perma.cc/V9R5-ZQ5N]. 
{: .fs-2}
<sup>109</sup>. *See* V. Gerard Comizio, *Virtual Currencies: Growing Regulatory Framework and Challenges in the Emerging Fintech Ecosystem*, 21 N.C. BANKING INST. 131, 138 (2017). 
{: .fs-2}
<sup>110</sup>. *Id.*
{: .fs-2}
***

the radar of regulatory bodies, and many consumers were at risk for shams and heists.<sup>111</sup> Mt. Gox—and other exchanges that followed—were lucrative targets for hackers because exchanges controlled the users’ private keys.<sup>112</sup> One of the largest heists occurred in August 2014 when 850,000 bitcoins, worth $387 million, were stolen from the wallets managed by Mt. Gox.<sup>113</sup>

Today, there are over 260 cryptocurrency exchanges, including ***Coinbase*** founded in 2012 in the United States;<sup>114</sup> ***Huobi***, founded in China in 2013;<sup>115</sup> and** *Binance***, founded in China in 2017, but which has since moved to Malta.<sup>116</sup> Many exchanges now comply with regulations, including Know Your Customer (KYC) and Anti-Money Laundering (AML) requirements.<sup>117</sup> For example, Coinbase had money transmitter licenses from 44 U.S. states and a New York State Virtual Currency License by 2019.<sup>118</sup> Coinbase also has commercial criminal insurance that is greater than the value of digital currency maintained in online storage (ninety-eight percent of the private keys are stored offline).<sup>119</sup> Increased compliance means a loss of user anonymity, a consequence that runs counter to the Cypherpunk values of the initial Bitcoin adopters.

***
<sup>111</sup>. *See id. *at 140. 
{: .fs-2}
<sup>112</sup>. *See id. *
{: .fs-2}
<sup>113</sup>. *Japan Arrests MtGox Bitcoin Head Over Missing $387m*, ALJAZEERA (Aug. 1, 2015), [https://perma.cc/SX42-XAEW]. 
{: .fs-2}
<sup>114</sup>. Trautman & Harrell, *supra* note 55, at 1058. 
{: .fs-2}
<sup>115</sup>. Eunice Yoon, Behind *China’s Love Affair with Bitcoin,* CNBC (Dec. 20, 2013), [https://perma.cc/C8AE-RKA4]. 
{: .fs-2}
<sup>116</sup>. *See* Priyeshu Garg, *Binance Set to Move to Malta with Their Prime Minister Welcoming*, BLOCKONOMI (Mar. 31, 2018), [https://perma.cc/UAJ4-445M]. Coin.Market tracks cryptocurrency exchanges on its website. *See Top Cryptocurrency Exchanges List*, COIN.MARKET, [https://perma.cc/VR6N-L2HZ] (last visited Feb. 27, 2020). 
{: .fs-2}
<sup>117</sup>. *See* Craig Adeyanju, *What Crypto Exchanges Do to Comply with KYC, AML and CFT Regulations,* COIN TEL. (May 17, 2019), [https://perma.cc/KDN8-JYTJ]. 
{: .fs-2}
<sup>118</sup>. *See Licenses*, COINBASE: LEGAL, [https://perma.cc/CG3M-YHBH] (last visited Feb. 27, 2020) (not licensed in California, Hawaii, Indiana, Massachusetts, Missouri, or Wisconsin); Virtual Currency License, N.Y. DEPT. FIN. SERVS. (Jan. 17, 2017), [https://perma.cc/RCP6-EKGH]. 
{: .fs-2}
<sup>119</sup>. *See* Carol Goforth, *The Lawyer’s Cryptionary: A Resource for Talking to Clients About Crypto-Transactions*, 41 CAMPBELL L. REV. 47, 67 (2019); *Security,* COINBASE, [https://perma.cc/5X5T-2EWN] (last visited Feb. 27, 2020).
{: .fs-2}
***

### C. Public Platforms with Smart Contracts
**Ethereum** was the first blockchain platform designed to overcome Bitcoin’s limited functionality as a single application that only tracks payments.<sup>120</sup> Launched in 2015, Ethereum uses smart contracts so that developers can build decentralized applications on the platform.<sup>121</sup> A smart contract, a concept developed by Nick Szabo in 1994, is “a piece of software that stores rules of negotiating the terms of a contract, automatically verifies [the contract,] and [then] executes the terms.”<sup>122</sup> Anything that can be coded within the rules of logic can be programmed into a smart contract that is secured, automatically executed, and permanently stored on a blockchain.<sup>123</sup> (The legality and limitations of smart contacts are addressed in other papers in this issue.) Smart contracts are commonly used to automatically move value around accounts based on agreed upon conditions.<sup>124</sup> Use cases include lotteries; voting; crowdsourcing; asset sharing; asset tracking; identity management; bidding; rating; gaming; and gambling.<sup>125</sup> As of January 2020, there were

***
<sup>120</sup>. *See* Chris Brummer & Yesha Yadav, *Fintech and Innovation Trilemma,* 107 GEO. L.J. 235, 272 (2019). Vitalik Buterin wrote the 2015 Ethereum white paper when he was only 19 years old. Orna Rabinovich-Einy & Ethan Katsh, *Blockchain and the Inevitability of Disputes: The Role for Online Dispute Resolution*, 2019 J. DISP. RESOL. 47, 51 (2019). Buterin, Gavin Wood, and Jeffrey Wilcke began work on Ethereum by launching The Ethereum Foundation, a non-profit organization based in Switzerland. *History of Ethereum,* ETHEREUM HOMESTEAD, [https://perma.cc/M8XD-D3PB] (last visited Mar. 16, 2020). 
{: .fs-2}
<sup>121</sup>. *See* Rabinovich-Einy & Katsh, *supra* note 120, at 51. 
{: .fs-2}
<sup>122</sup>. MJ Kim, *The Future of Blockchain Technology: Smart Contracts,* TECHNODE (Nov. 14, 2016), [https://perma.cc/63RY-GZE6]. 
{: .fs-2}
<sup>123</sup>. Tsui S. Ng, *Blockchain and Beyond: Smart Contracts*, BUS. L. TODAY, Sept. 2017, at 1. 
{: .fs-2}
<sup>124</sup>. *Id.* at 1-2. 
{: .fs-2}
<sup>125</sup> In general, smart contracts can be classified as either ‘deterministic’ or ‘nondeterministic.’
{: .fs-2}
_**A deterministic smart contract**_ means that [terms of the agreement] . . . can execute autonomously without the need for any outside information. A lottery is a good example. A smart contract for a lottery could define the time period when people could send value to the smart contract account to ‘buy’ lottery tickets. The smart contract could specify how the winning lottery number would be selected, perhaps by taking the hash of a randomly selected block and awarding the account that is closest to that number as the winner. The smart contract could automatically transfer the money to the winning account. If the lottery was regulated, the smart contract could be coded to deduct taxes. 
{: .fs-2}
_**A non-deterministic smart contract**_ means that outside information is needed to execute the contract. Horse race betting is an example. Like a lottery, a smart contract for horse race betting could be coded to define when people could send value to the smart contract account
{: .fs-2}
***

nearly 5,000 smart contracts deployed on Ethereum, although many of them are inactive.<sup>126</sup> Because Ethereum uses the same consensus mechanism as Bitcoin (called a “proof-of-work”), it improved but still has some of the same limitations as Bitcoin as far as resource consumption<sup>127</sup> and few TPS (about fifteen TPS).<sup>128</sup>

***EOS*** was developed to keep all of the advantages of a public blockchain platform like Ethereum—open, secure, and decentralized—but without the latency, scalability, and resource intensity. Launched in 2018, anyone can transact and build apps using smart contracts on EOS.<sup>129</sup> Blocks are produced about every 500 milliseconds due to a faster consensus mechanism called *Delegated Proof-of-Stake (DPoS)*. <sup>130</sup> Rather than having miners compete, EOS users stake their EOS token to elect twentyone block producers, with each of the twenty-one producers getting a turn to create the next block.<sup>131</sup> Block producers are rewarded with the issuance of new EOS tokens.<sup>132</sup>

### D. Private Platforms with Smart Contracts
Traditional enterprises mostly ignored Bitcoin for the first few years, but enterprises began to explore the strategic

***
to place their bets. The rules for adjusting odds could also be mechanized in the contract. However, smart contracts for horse racing cannot run autonomously; they need outsiders (called ‘***oracles***’) to inform the smart contract of the winning animal. Unlike trusted third parties, an oracle in this scenario does not control the funds, the smart contract does. LACITY, *supra *note 14, at 60 (emphasis added). 
{: .fs-2}
<sup>126</sup>. *DApp Statistics: Platforms*, STATE OF THE DAPPS, [https://perma.cc/4H83-GCEJ] (last visited Mar. 5, 2020). 
{: .fs-2}
<sup>127</sup>. *Ethereum Energy Consumption Index (Beta),* DIGICONOMIST, [https://perma.cc/4WZ4-G5W4] (last visited Mar. 5, 2020). Digiconomist, a site that tracks Ethereum’s energy consumption, reports that a single transaction consumes enough electrical energy to power an average U.S. household for 1.2 days. *Id. *
{: .fs-2}
<sup>128</sup>. Abhimanyu Krishnan, *Vitalik on Ethereum: “Right Now It Can Process 15 Transactions Per Second. Really, We Need 100,000,*” INVEST IN BLOCKCHAIN (Mar. 21, 2019), [https://perma.cc/8LZK-JGRF]. 
{: .fs-2}
<sup>129</sup>. *About Us,* EOISO, [https://perma.cc/6YCU-YVNF] (last visited Mar. 5, 2020). *See Why Build on EOSIO?*, EOSIO, [https://perma.cc/X6C8-ANUP] (last visited Mar. 5, 2020). 
{: .fs-2}
<sup>130</sup>. *Coins*, CRYPTOSLATE, [https://perma.cc/66CV-B9D2] (last visited Mar. 5, 2020). 
{: .fs-2}
<sup>131</sup>. *See Block Producers*, BLOKS.IO, [https://perma.cc/79YT-B6RW] (last visited Mar. 5, 2020). 
{: .fs-2}
<sup>132</sup>. Chrisjan Pauw, *EOS BP, Explained,* BEQUANT, PRO (May 23, 2019), [https://perma.cc/NV8Z-VB7C].
{: .fs-2}
***

opportunities and threats posed by Bitcoin and related blockchain technologies by 2014 with the formation of R3, a consortium of global banks based in New York City.<sup>133</sup> Additional consortia, working groups, and non-profits began to define blockchain standards and develop code bases for enterprise applications.<sup>134</sup> There are nearly 103 blockchain consortia of significance.<sup>135</sup> In 2017, three significant code bases for private blockchains were released as open source software. JP Morgan released ***Quorum***, a private version of Ethereum;<sup>136</sup> R3 released ***Corda***, a peer-topeer code base aimed at enterprises that want strict data and transaction privacy;<sup>137</sup> and the HyperLedger Project released ***Fabric***, much of whose code was donated by IBM.<sup>138</sup> These ***permissioned blockchains***—where joining the network is by invitation-only—use some form of Practical Byzantine Fault Tolerance (PBFT) as a consensus protocol.<sup>139</sup> With PBFT, nodes need permission to serve as validator nodes, forming a member list, which provides traditional enterprises with the confidentiality and control they need.140 So, what do enterprises actually build with these blockchain innovations? The next section covers use case examples.

***
<sup>133</sup>. *Blockchain Applications in Banking*, DELOITTE, [https://perma.cc/5DCJ-2SZB] (last visited Mar. 5, 2020). 
{: .fs-2}
<sup>134</sup>. LACITY, *supra* note 14, at 29. 
{: .fs-2}
<sup>135</sup>. *Top Four Enterprise Blockchain Consortia Trends*, ESG INTELLIGENCE (June 19, 2019), [https://perma.cc/79AD-XCZK]. 
{: .fs-2}
<sup>136</sup>. Robert Hackett, *Why J.P. Morgan Chase Is Building a Blockchain on Ethereum*, FORTUNE (Oct. 4, 2016), [https://perma.cc/3D8F-Z9HZ]. 
{: .fs-2}
<sup>137</sup>. *The Network,* CORDA, [https://perma.cc/RZW2-U3DT] (last visited Mar. 2, 2020); RICHARD GENDAL BROWN, THE CORDA PLATFORM: AN INTRODUCTION 6 (2018), [https://perma.cc/G8J9-A39H]. 
{: .fs-2}
<sup>138</sup>. BRENN HILL ET AL., BLOCKCHAIN DEVELOPER’S GUIDE 139 (2018). 
{: .fs-2}
<sup>139</sup>. Libo Feng et al., *Scalable Dynamic Multi-Agent Practical Byzantine FaultTolerant Consensus in Permissioned Blockchain,* 8 APPLIED SCIS. 1, 1 (2018). 
{: .fs-2}
<sup>140</sup>. With PBFT, a node from the member list is selected as leader for the next round of validation. Brian Curran, *What is Practical Byzantine Fault Tolerance? Complete Beginner’s Guide,* BLOCKONOMI (May 11, 2018), [https://perma.cc/9J4F-3AYM]. A client node sends a request to the leader node to validate a transaction. *Id.* The leader node multicasts the request to all the other authorized nodes. *Id*. The authorized nodes execute the request independently and then send to each other and reply to the client. *Id*. The client waits for a certain percentage of replies to confirm validation, typically waiting for 2/3 of the nodes to agree. *Id*. The leader node changes for the next round. *Id.*
{: .fs-2}
***

***

#### Table of Contents
{: .no_toc}

<ul><li> <a href="/docs/cryptocurrency/crypto-and-blockchain-fundamentals-1/">I. FROM THE “INTERNET OF INFORMATION” TO THE “INTERNET OF VALUE”</a></li><li> <a href="/docs/cryptocurrency/crypto-and-blockchain-fundamentals-2/">II. THE INGENUITY AND LIMITATIONS OF BITCOIN</a></li><li> <a href="/docs/cryptocurrency/crypto-and-blockchain-fundamentals-3/">III. Beyond Bitcoin - Other Technical Innovations</a></li><li> <a href="/docs/cryptocurrency/crypto-and-blockchain-fundamentals-4/">IV. BLOCKCHAIN-BASED APPLICATION EXAMPLES</a></li><li> <a href="/docs/cryptocurrency/crypto-and-blockchain-fundamentals-5/">V. New Fundraising Models</a></li><li> <a href="/docs/cryptocurrency/crypto-and-blockchain-fundamentals-6/">VI. WHY THE “INTERNET OF VALUE” NEEDS LEGAL PRACTITIONERS</a></li></ul>

</div>

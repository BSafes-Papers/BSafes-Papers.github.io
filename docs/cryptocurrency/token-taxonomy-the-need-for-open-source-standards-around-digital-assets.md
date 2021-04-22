---
layout: default
title: § TOKEN TAXONOMY - The Need for Open-Source Standards Around Digital Assets
parent: Cryptocurrency 
nav_order: 9801000 
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
This is the mobile-friendly web version of the [original article](https://www.blockchainresearchinstitute.org/wp-content/uploads/2020/02/Tapscott_Token-Economy_Blockchain-Research-Institute.pdf).

![The Need for Open-Source Standards Around Digital Assets](https://statics.bsafes.com/images/papers/Tapscott_Token-Economy_Blockchain-Research-Institute-28.png)
### BLOCKCHAIN RESEARCH INSTITUTE
{: .no_toc }
# TOKEN TAXONOMY
{: .no_toc }
## The Need for Open-Source Standards Around Digital Assets 
{: .no_toc }

Don Tapscott
Blockchain Research Institute

February 2020

<div class="youtube-container">
<iframe width="100%" src="https://www.youtube.com/embed/isuAPyuqS7Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen class="youtube-video"></iframe>
</div>

**Video:** Understand blockchain in under 7 minutes: Don Tapscott with Lloyds Bank

### A BLOCKCHAIN RESEARCH INSTITUTE BIG IDEA WHITE PAPER

***

### Realizing the new promise of the digital economy
{: .no_toc}
In 1994, Don Tapscott coined the phrase, “the digital economy,” with his book of that title. It discussed how the Web and the Internet of information would bring important changes in business and society. Today the Internet of value creates profound new possibilities.

In 2017, Don and Alex Tapscott launched the Blockchain Research Institute to help realize the new promise of the digital economy. We research the strategic implications of blockchain technology and produce practical insights to contribute global blockchain knowledge and help our members navigate this revolution.

Our findings, conclusions, and recommendations are initially proprietary to our members and ultimately released to the public in support of our mission. To find out more, please visit www.blockchainresearchinstitute.org.

### Blockchain Research Institute, 2020
{: .no_toc}
Except where otherwise noted, this work is copyrighted 2020 by the Blockchain Research Institute and licensed under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International Public License. To view a copy of this license, send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA, or visit creativecommons.org/ licenses/by-nc-nd/4.0/legalcode.

This document represents the views of its author(s), not necessarily those of Blockchain Research Institute or the Tapscott Group. This material is for informational purposes only; it is neither investment advice nor managerial consulting. Use of this material does not create or constitute any kind of business relationship with the Blockchain Research Institute or the Tapscott Group, and neither the Blockchain Research Institute nor the Tapscott Group is liable for the actions of persons or organizations relying on this material.

Users of this material may copy and distribute it as is under the terms of this Creative Commons license and cite it in their work. This document may contain material (photographs, figures, and tables) used with a third party’s permission or under a different Creative Commons license; and users should cite those elements separately. Otherwise, we suggest the following citation:

Don Tapscott, “Token Taxonomy: The Need for Open-Source Standards Around Digital Assets,” Blockchain Research Institute, 19 Feb. 2020.

To request permission for remixing, transforming, building upon the material, or distributing any derivative of this material for any purpose, please contact the Blockchain Research Institute,
www.blockchainresearchinstitute.org/contact-us, and put
“Permission request” in subject line. Thank you for your interest!

***

1. TOC
{:toc}

## Contents

- Idea in brief

- Tokens and digital assets
    - The state of the token
    - First-principles thinking

- Introducing the Token Taxonomy Framework
    - Characteristics of tokens
    - Types of tokens
    - Behaviors and property sets of tokens

- Benefits of shared token standards.
    - Ease of use
    - Interoperability
    - Communication
    - Security and speed

- Our role in co-creating standards
    - The need for collaboration
    - The need for stewardship
    - The need for certification

- Conclusions

- About the author

- About the Blockchain Research Institute

- Notes

## Idea in brief
 - » Digital assets, sometimes called tokens, are poorly understood. That may be why they are used to describe a variety of things, some of which are contradictory. We know that they are important, but we need greater concurrence on what they are and how we define them in terms of code. 

- » The Token Taxonomy Initiative (TTI) is a new standardization effort championed by a who’s who of enterprise blockchain, from Accenture to Web3 Labs.<sup>1</sup> It will help unify our understanding of the token economy without sacrificing the decentralization that makes it so powerful. 

- » The TTI’s Token Taxonomy Framework (TTF) is a firstprinciples model for understanding tokens. It starts with token types and progresses to token properties, with a goal of enabling anyone—technologist, businessperson, or regulator— to understand what is happening and how to take part in token projects. 

- » Standardization requires a commitment to collaborating with competitors, stewarding shared creations faithfully, and developing certification programs that make it easier for users to detect fakes and harder for unscrupulous designers to claim the use of standards while deviating from those standards. 

- » The benefits of shared token standards are many: increased ease of use, improved interoperability, easier communication, and faster and more secure development of the token projects that we’d like to see in the world.

## Tokens and digital assets

### The state of the token

Few concepts are more widely discussed and poorly understood in today’s blockchain world than the token. The world seems to know that tokens are important, but little else; the word token is used in myriad ways today, many of which conflict. 

Perhaps the most common modern usage of token is as the latter part of what some call “security tokens,” by which they mean cryptocurrencies that governments are justified in regulating. Security tokens are the ostensible antithesis of “utility tokens,” by which crypto enthusiasts mean cryptocurrencies that governments should not clamp down on—especially the ones they’re developing for their blockchains.<sup>2</sup> The precise details of the possible difference between a utility token and a security token is irrelevant. What matters is that this use of the word token strongly implies that tokens are tantamount to cryptocurrencies, and that the polar extremes of “security” and “utility” are complementary halves of a collective whole.

One of the largest issues facing the blockchain community in the beginning of 2019 was the US Securities and Exchange Commission’s ruling that some cryptocurrency sales—most often branded as initial coin offerings (ICOs)—constituted unlicensed sales of securities.<sup>3</sup> It was an unspoken truth that most ICOs in the 2017 boom met the definition of a security. A few SEC indictments later, coin holders found themselves furiously tweeting and publishing Medium posts about their “utility tokens” to distance themselves from such coins.

Other recent uses of the word token, however, have little to do with cryptocurrencies. The phrase “non-fungible token” entered the blockchain lexicon with the emergence of an improvement ticket for the Ethereum mainnet that defined a standard for tokens (ERC-721) that represented unique, one-of-a-kind items.<sup>4</sup> The classic example, of course, is the game CryptoKitties, in which users collect, trade, and breed digital cat images. One ether is just like the other (except, perhaps, for their transactional histories), but each CryptoKitty is unique and owned by only one wallet.<sup>5</sup> That’s a far cry from digital money—but the CryptoKitty also received a token label.

![Belgium Antwerp Shipping Container Freight Cargo by Olaf](https://statics.bsafes.com/images/papers/token-taxonomy-the-need-for-open-source-standards-around-digital-assets-fig-1.png)

*Belgium Antwerp Shipping Container Freight Cargo by Olaf (olafpictures), 2012, used under Pixabay license, accessed 27 Jan. 2020.*

Both of the above uses are fairly standard and accepted as correct by the blockchain intelligentsia—but, as we know from practice and the still unneutralized force of entropy, there are far more ways to be wrong than right. Some folks have disparate and seemingly contradictory names for different types of tokens (e.g., work token, use token, investment token, asset token, payment token, etc.); others use token when they really mean contract. Marley Gray, chair of the Token Taxonomy Initiative, Enterprise Ethereum Alliance board member, and principal architect at Microsoft, said:

> *It’s tempting to put contract logic within your token. It would be like saying, “I’m going to create a token for a property title and I’m going to put the information and the logic for how it should be paid in the token itself.” That essentially makes your token nonreusable, because it has contract logic embedded within it that may not apply to the next sale of the title.*

> *Just as we don’t write our mortgages on the actual money we’re paying them with, because we need to reuse that money, we don’t want to do that [with tokens].<sup>6</sup>*

What’s more, an equal number of folks draw a bright line between token and coin as those who draw no distinction at all; some believe that tokens can exist only on a public blockchain whereas others are more permissive; and the list goes on.

The different interpretations and uses of the word token are many, varied, and collectively confusing. How should any interested outsider hope to build up a coherent definition of a token with so much contradictory information flying about?

First, we can acknowledge that tokens are incredibly important to the blockchain world. Nearly every introductory blockchain article dives into its own definition of the concept early on, as tokens are among the building blocks of blockchain technology. Second, as a community, we must align on what we mean by token if we hope to explain blockchain to the average consumer.

### First-principles thinking
In the face of such complexity, diving deeper into the weeds (e.g., by isolating what constitutes a security) isn’t useful. Instead, let’s attack the problem from a different angle—preferably one that starts with first principles.

In 2001, newly minted millionaire Elon Musk had a goal to make humanity a multi-planetary species, and a way to get us there: Mars Oasis. Doug Bierend, writing for *Vice*, explained the mission:

> *A small lander carrying a glass-enclosed greenhouse would be launched to the surface [of Mars]. Seeds embedded in dehydrated nutrient gels would activate when the little lander touched down, sending back images and data as the leafy cargo grew and died on the planet’s surface. It could reveal a lot about the viability of transporting life to Mars and sustaining it there—a worthy experiment indeed.<sup>7</sup>*

Musk wanted to excite the public and spur government investment by showing green plant life growing against a red backdrop. There was only one problem: rocket launches for such an experiment were prohibitively expensive. The cheapest launch vehicles NASA could offer were about $65 million; that price tag alone was triple Musk’s anticipated budget for the entire experiment. After exploring other options (at one point even asking Russia to sell him an old ICBM), he found nothing in the known universe that could achieve the price point he needed.<sup>8</sup>

That would have been the end of the story for most people. But Musk is not most people. Using first principles thinking, he disputed the necessity of the constraints the world imposed upon him. In an interview with Kevin Rose, Musk said:

> *I think it’s important to reason from first principles rather than by analogy. The normal way we conduct our lives is we reason by analogy. We are doing this because it’s like something else that was done, or it is like what other people are doing. Slight iterations on a theme. It’s mentally easier. …*

> *First principles is a physics way of looking at the world. What that really means is you boil things down to the most fundamental truths … and then reason up from there. That takes a lot more mental energy.<sup>9</sup>*

Applying first-principles thinking to the cost of a rocket, Musk concluded that the market was underperforming relative to what was physically possible. He discovered that the cost of raw materials needed to construct a rocket is just around two percent of the total cost, which meant that he had an opportunity to build rockets more cheaply.<sup>10</sup> Recognizing an opportunity to carry on the mission of Mars Oasis, he founded SpaceX shortly thereafter.<sup>11</sup>

## Introducing the Token Taxonomy Framework
Launched in April 2019, the Token Taxonomy Framework (TTF) is an attempt to make sense of tokens by going back to first principles.

In early November 2019, a wide-spanning group of blockchain organizations that included the core players in enterprise blockchain—Accenture, Adhara, Banco Santander, Clearmatics, ConsenSys, Digital Asset, Envision Blockchain, EY, Hedera Hashgraph, IBM, Intel, ioBuilders, Itau, J.P.Morgan, Komgo, Microsoft, R3, Web3 Labs, and members of the Enterprise Ethereum Alliance, among others—released the TTF Version 1.0 as the first output of the Token Taxonomy Initiative, an independent organization hosted by the Enterprise Ethereum Alliance (EEA).<sup>12</sup> Ron Resnick, executive director of the EEA and a major proponent of the initiative, explained:

> *The Token Taxonomy Framework deals with how digital assets are exchanged and how we can accomplish global adoption of digital assets. In order for such assets to be interoperable as deployed by developers, and for oversight exchanges by governments and regulators to be implemented in the most efficient manner, there needs to be some model for how they all communicate using the same terminology, the same language, and in a way that allows oversight and accountability*

> *There needs to be some universal language or framework of how tokens are defined and utilized that’s flexible, adaptable, and expandable to be used for the myriad use cases that will emerge. That’s the vision. It’s really simple: the global economy of the future is going to be a tokenized economy; and for that to happen, we have to define tokens in a consistent way.<sup>13</sup>*

That’s a grand vision, but the TTF appears to be up to the task. We believe that it’s a truly impressive work that should prove to be an industry-altering standard, as long as the community continues to engage and develop it. 

![Boxes Drawers Mailboxes Residential Mailboxes Wood ](https://statics.bsafes.com/images/papers/token-taxonomy-the-need-for-open-source-standards-around-digital-assets-fig-2.png)
*Boxes Drawers Mailboxes Residential Mailboxes Wood by Pexels, 2016, used under Pixabay license, accessed 27 Jan. 2020.*

The TTF includes a set of core concepts and terms, with which you can intuitively understand and technically describe existing token projects; a composition framework that helps you build new kinds of tokens from the ground up; examples and real-world token specifications with portable, compartmentalized definitions of tokens for a variety of extant use cases; and much more.

Note that Ethereum and other technology platforms are not on that list. The TTF is intentionally platform-agnostic and doesn’t even take sides on blockchains versus databases. Paul DiMarzio, director of community for the EEA, said:

> *With the TTF, there’s a difference between specification and implementation. We only focus on the specification part of it. We want to make sure that every token has a common and consistent set of behaviors and characteristics that are well defined and well known and well understood. Once you get that settled, then wherever you want to implement it, you’re going to use whatever the rules and regulations are of that particular framework.*

> *We will provide sample code, so, for instance, if a member is very much into the Ethereum space and they understand ERC-20s really well, they may start to provide some samples to how you would actually implement those specifications in ERC-20. Fabric guys will do the same for their platform, and so on.<sup>14</sup>*

In other words, the framework is intended to be descriptive, not prescriptive. A team from the Coalition of Automated Legal Applications described the challenge well:

> *Whenever engineers set out to develop a new standard to unite several competing standards, they succeed only in adding yet another standard. The current proliferation of chat protocols perfectly illustrates this problem. iMessage, Signal, Telegram, Slack, Discord, WhatsApp, Messenger, Hangouts, Skype, WeChat or just plain SMS: it takes dozens of chat clients to communicate with everyone, and none of them are willing to talk to each other.<sup>15</sup>*

Marley Gray of TTI elaborated:

> *The Token Taxonomy Framework addresses the interconnection problem from the top down, describing in a technology-neutral way how you can standardize. I’ve done lots of integration projects over my 30 years of experience in the field, particularly at the blockchain or the data layer where I’m connecting two different databases together, point to point.*

> *It’s achievable and it’s doable, but it’s really brittle and just extremely susceptible to minor changes on one end completely breaking your bridge between the two. So those point-to-point connections are really hard to maintain over time. The successful integration patterns that I’ve seen, and repeatedly, are to abstract one level up to create the common set.*

> *If you think about ODBC [open database connectivity]—how do we allow applications that use relational databases not to have to be specifically programmed for just an Oracle database or a SQL database—you can write it once and it should still work if you point it to any ODBC-compliant database. That is a successful integration, still around today.*

> *We did the same thing for printers. Back in the day, you went and bought a printer and each application had to have a driver for that program to be able to print to that printer, which was a really horrible experience when you could go buy a brandnew printer and discover that WordPerfect wouldn’t print to it.*

> *That’s why we’re solving the problem by creating a common abstraction, but not being so abstract where it completely removes any differences between those platforms and doesn’t let the true capabilities shine.<sup>16</sup>*

The TTF is not just another standard, it’s a metastandard: something that can stand above other interoperability protocols, remain agnostic on many of the contentious implementation questions that other protocols squabble over, and describe (not prescribe) what’s happening so the rest of the world can make sense of the new token economy. Gray continued with a helpful analogy to drive home this point: the TTF is like the standardization of railroad track widths.

> *The framework encourages learning and iterative improvement over time. First, it describes railroad tracks. It does not say how wide they should be or any of the specifics. It just says these are railroad tracks. Railroad tracks serve this business purpose.*

> *You don’t specify how wide the tracks are until you put them in context with all of the other things that make them up … . What’s the weight of the train? How fast is the train going to travel? But we won’t know those things until you get to that.*

> *Then when edits occur, you keep the historical record, because it’s using GitHub behind the scenes. You can say, “Oh, you know what, they did try the 42 inches rail width before and they changed it to 60 and, oh, this is why.”<sup>17</sup>*

The TTF is an attempt to describe tokens precisely as they are today, without judgment but with a more robust structure. We will turn to the TTF’s structured approach to understanding how tokens are composed shortly, but first, we need to make sure we’re on common ground in understanding precisely what tokens are.

### Characteristics of tokens
Tokens may have different features and purposes, but all tokens have several characteristics in common: they are valuable, representative, digital, distinct, and authentic.

![Rails Soft Gleise Railway Railway Line Train](https://statics.bsafes.com/images/papers/token-taxonomy-the-need-for-open-source-standards-around-digital-assets-fig-3.png)
*Rails Soft Gleise Railway Railway Line Train by Michael Gaida (MichaelGaida), 2018, used under Pixabay license, accessed 27 Jan. 2020. Cropped to fit.*

First, tokens are *valuable* in the sense that we are usually able to value them (i.e., determine their value) in terms of a global standard such as the US dollar and within a context such as the Bitcoin or Ethereum blockchain or a cryptocurrency exchange. For example, Bitcoin’s monetary policy ensures the scarcity of tokens within the system; and its use of cryptography and its proof-of-work consensus mechanism, which consumes a calculable amount of energy to append blocks and mint bitcoins, make it very costly to steal existing coins and difficult to hack otherwise. So bitcoin is valuable within this system and has value in the marketplace.<sup>18</sup>

Second, tokens are *representative* in the sense that they stand for the holder’s claims to an asset, resource, or right. Sometimes, tokens represent physical objects like artwork, gold, or land. Other times, tokens represent rights to digital goods and services like intellectual property, where tokens provide access to members-only content, use of a design patent, cloud computing, or a skin in *Fortnite.* <sup>19</sup>

Third, tokens are *digital*, often stored in digital wallets and recorded on a blockchain. While tokens could be representations of physical objects such as a deed to land or the title to an automobile, the deeds and titles themselves are digital. We suppose that the physical coins your local coin-operated game room uses might also have a claim to be tokens, but that’s not what we’re talking about here. Nor are we talking about the security tokens stored on fobs and used to authenticate identity or to open or close electronic locks.

Fourth, tokens are *discrete*. We can verify the number of tokens; and we can distinguish one token from another, just as we can differentiate one dollar bill from another. Tokens are not observerdependent: any honest audit should reveal that a token to you is the same as a token to me. As you’ll see, this quality should also be true of the traits and behaviors of a token. There should be no ambiguity in the token economy.

Fifth, and perhaps most important, tokens are *authentic*; that is, we are able to verify their authenticity. In a human context, authenticity is an operationalized form of trust. As much as we love to use the word trustless in the blockchain world, we must remember that the whole system works only if people believe that our tokens are as real as the paper money, license, or deed they hold in their hand.

It may be verifiably and objectively true that a proof-of-work token is unforgeable—but if you go to a Fortune 500 chief executive today and launch into a monologue on SHA-256, the Byzantine generals’ problem, and UTXOs (unspent output from bitcoin transactions) to explain why, you’re not going to leave that meeting with an additional budget allocation for your token project.

How to build such trust and secure such investment is a much larger question, and one that touches on fundamental questions of how the public learns to trust new technologies. For the sake of this analysis, we’ll just say that, to convince people to trust something, you must help them to understand how it works or what it can do for them. (One of those two usually suffices; consider the complexity of jet propulsion and our willingness to board planes nonetheless, because we can predict the engines will do us some good and not hurt us.)

This final goal—trust—is the real magic of the TTF. It’s a way for anyone and everyone to speak the same language, understand what tokens are, and believe that these digital representations of valuable things really do what the tech guys claim they can do.

### Types of tokens
The first major building block used by the TTF to describe tokens is what they call types: whether each instance of a token is unique or interchangeable. They call unique tokens non-fungible and interchangeable tokens fungible. We’ve already introduced this concept above, but it bears repeating because it’s so fundamental— we all must understand this distinction to make sense of tokens. US dollars are fungible: trading $1 for $1 is trivial, because each instance of a dollar (each bill) is functionally equivalent to every other instance. Artwork is non-fungible: trading one painting for another is a nontrivial transaction because the value of even similar paintings by the same artist will vary significantly.

Interestingly, the TTF also builds on our understanding of fungibility by proposing a third type of token: a hybrid. A hybrid, for example, is like a general admission concert ticket. Let’s say there’s a big Metallica concert tomorrow, and you buy a general admission ticket. The ticket is fungible in terms of seating: you have to storm the gates if you want a front row seat. But it’s non-fungible in relation to the other nights of the tour: if you miss the concert tomorrow, you can’t use same ticket for the next day. We can think of such a concert ticket as a fungible token for seating nested inside of a non-fungible token for concert date: a hybrid.

### Behaviors and property sets of tokens
After defining the token type, the TTF progresses to token b*ehaviors and properties,* or unique compositional elements. Ron Resnick, executive director of the EEA, explained these concepts through a music analogy:

> *The language of music is simple. There are 12 notes and there are rules for how you compose, but look at the complexity that you can build—solutions, types, styles, and instruments are infinite. That’s how we should define tokens. We should have rules of behavior for the tokens, rules of how we define their properties.*

> *We should all agree on those rules, and then it is very simple for the folks who learn how to use the framework to share it with the technology folks in their organizations, and those folks can decide what underlying technology they’ll use, which could be any resource as long as it conforms to the framework that will be offered.<sup>20</sup>*

Behaviors are rules for how tokens behave—a permissible action or restriction—and property sets are data elements that a token must have. An example of a behavior is a singleton: a non-fungible singleton is a one-of-a-kind digital asset represented by a solitary token; it is *indivisible*. In contrast is the behavior *divisible* (with the alias of *subdividable*, denoted by d), which defines how many constituent pieces a token can be split into (e.g., a dollar that can be divided into 100 cents, or two decimal places to the right of zero). A property set is a descriptive value that doesn’t achieve anything within the token system itself but has external meaning, like a stockkeeping unit (SKU) or a serial number.

Ultimately, there are too many property sets and behaviors for us to do justice to them all here—plus, Resnick called the full list in version one of the TTF “a work in progress.” The Token Taxonomy Initiative welcomes feedback. Its organizers hope that its members will dream up properties they haven’t yet included in the framework and then submit them to GitHub as pull requests.<sup>21</sup>

> #### Emoney token spec
{". no_toc}
The following example, adapted from a token spec called “Emoney” by Julio Faura from Adhara and Daniel Lehrner from ioBuilders, is a set of behaviors that describe a token that acts like money. Can you think of any behaviors that you could add to this list to make the token perform differently?

>- » *Roles that are definable and assignable*: This behavior allows users to define which role(s) to create and which behavior(s) to assign to each role in the template definition. It enables users to check whether other users have the role and the authority to invoke whatever behavior they’re invoking. Think of the different decision rights of the different roles of a company’s executive team and its corporate board, all defined by the company’s charter.

>- » *Delegable*: A token class that implements this behavior allows token owners to delegate certain behaviors to other parties or accounts, that may invoke these behaviors on behalf of the owners. In other words, those other parties or accounts may automatically perform the delegated behaviors (up to a certain allowance) without seeking permission. 

>- » *Transferable*: Every token has an owner. The transferable behavior enables the owner to transfer ownership of the token to another party or account. This behavior is often implied by other behaviors that might exist (e.g., redeemable, sellable, etc.). This behavior is delegable. 

> - » *Holdable*: Every token has an owner. A hold specifies a payer, a payee, a maximum amount, a notary, and an expiration time. When the hold is created, the specified token balance from the payer is put on hold and won’t transfer until the hold is executed or released. Only the notary can execute the hold, which triggers the transfer of the tokens (partially or for the full amount) from the payer to the payee. If a hold is released, either by the notary at any time or by anyone after the expiration, no amount is transferred and the held balance is available again to the payer. This behavior is also delegable. 

> - » *Compliant*: A regulated token must comply with several legal obligations, especially know-your-customer and anti-money laundering requirements. If the necessary checks must occur off-chain, the token transfer becomes centralized and requires a second confirmation step. A compliant token fulfills all legal requirements on-chain without interacting with an off-chain entity. 

> - » *Burnable*: A token class that implements this behavior supports the decommissioning (or burning) of token instances of the class. This doesn’t delete a token but places it in a permanent nonuse state. Burning is a oneway and irreversible operation. This behavior is delegable.

> - » *Mintable*: A token class that applies this behavior supports the minting or issuing of new token instances in the class. These new tokens can be minted and belong to the owner or minted to another account. Mintable is technically delegable, but roles definition and assignment ought to control its delegation.<sup>22</sup>

See TTF’s draft specification library for other examples such as bonds, inventory, license or diploma, loyalty, original art, reputation, rewards, and reserved tickets.<sup>23</sup>

## Benefits of shared token standards
The goal of a standard like the TTF is, at its core, interoperability at both the human and technological levels. In this section, we’ll consider how standardization like that achieved by the TTF can help move blockchain technology forward over the long run.

### Ease of use
The TTF is far more than just a list of definitions. It has resources to help practitioners make their own token projects. The first is the composition framework—effectively a set of rules that help designers put the different behavioral pieces together into one coherent, easily digestible whole. The Token Taxonomy Initiative has devised a formulaic syntax for defining tokens in one string of characters. Instead of describing your token as “a fungible parent token that allows new tokens to be minted, and non-fungible child token that cannot be minted, where both classes of token are transferable,” you can write:

> [τF{m} (τN{~m}){t}] “A fungible parent token τF{} that allows new tokens to be minted m, and child token () that is nonfungible τN{} and cannot be minted ~m, where both classes of token are transferable t.”

A concept that business folks might find more approachable is the “behavior group,” basically a prepackaged set of behaviors that is more easily understood in combination than in its individual components. You can apply the “supply control” group, for instance, to a token that you wish to make mintable and burnable and to have roles. This is a useful abstraction, as you don’t want to always reference each individual behavior; it’s easier to remember such properties in subsets.

The Token Taxonomy Initiative is also hard at work prototyping a token designer, a WYSIWYG editor for tokens.<sup>24</sup> Business folks might not know how to read a token formula, but they should understand what happens when you drag and drop different puzzle-piece-looking behavior groups and property sets onto a canvas to construct a unique, coherent, templatized token. Marley Gray explained,

> *So the perfect end state here is for a business user, once they’ve done some basic education and they get the basic terms, to have a playground with the token designer. *

> *This can let a businessperson start by dragging and dropping a design surface and saying, “I want to create a singleton token.” The framework would automatically start building the token itself. Then, within that same tool, they can set the individual values, do the same thing for property sets, or even bring up existing tokens—maybe a token that’s in the market today, or in the TTF—and pull it up in this designer and be able to learn about it by just hovering over the individual artifacts that make up that token.*

> *They’re all using the TTF to understand and model new tokens based on their business requirements. On the technical side, this doesn’t mean you have a [readily deployable] token. But it means you have a solid set of business and technical requirements that someone can go implement.<sup>25</sup>*

Together, these tools can help anyone interact with tokens; the tools of the TTF are far more approachable than any programming language or white paper. Standards are only useful when people know how to use them, so the TTF does a great job of democratizing access to tokens, thereby pushing the blockchain community forward.

![Measure Yardstick Tape Ruler by Ariel ](https://statics.bsafes.com/images/papers/token-taxonomy-the-need-for-open-source-standards-around-digital-assets-fig-4.png)
*Measure Yardstick Tape Ruler by Ariel (arielrobin), 2016, used under Pixabay license, accessed 27 Jan. 2020.*

### Interoperability
In the enterprise context, interoperability with other blockchain protocols is debatably less important than integration with legacy enterprise IT systems. Despite the nimble nature of their advance scouts tasked with blockchain initiatives, changing the legacy infrastructure of a major enterprise is an incredible challenge.

As goes the analogy, an incumbent enterprise is like a cruise ship—it has amassed momentum in a direction, such that the force required to change course must be great enough and applied early enough to overcome inertia and take effect before it’s too late. A start-up is like a speed boat, zigging and zagging to dodge threats and catch opportunities.

Standards like the TTF will help enterprises get comfortable with integrating their systems with a blockchain protocol today, quelling fears that blockchain is a fad that will die and render their integration work fruitless. Marley Gray said that TTF is intentionally an “interface standard” rather than an “implementation standard,” which has helped to address this concern. He said,

> *The TTF is implementation-agnostic, but it essentially describes how you invoke a behavior, like a transfer or the transfer request, and it has a transfer response. Now, that doesn’t say how it’s actually coded in C# or in Java or Go; but rather, it says you should have an exposure that does a transfer, handles a transfer request, and it should return this as a response and describe that in business language. *

> *We’re already seeing code generation where people are doing a code gen from these specifications and implementing whether it’s a REST [representational state transfer] interface, or a messaging interface, because we have all of the data in here and it’s consistent. Now, if we can get the consistent naming, well, we should get to consistent interfaces across. *

> *That’s where we’re going next. Let’s create not an implementation standard, but essentially the interface standard. It’s one level higher up than ERC-20. ERC-20 is an interface for Solidity on a particular platform. This is, “Let’s abstract ERC-20 to a higher level and say it has a transfer request and response.”<sup>26</sup>*

That kind of predictability is necessary to secure long-term investment from modern businesses, and the stability of an industry group like the Token Taxonomy Initiative will do wonders for the budgets allocated to blockchain development projects at major enterprises.

### Communication
Business folks tend to have a natural ability to take a complex topic, abstract away all of the complexities, and end up with a vision of the future that’s incredibly compelling but totally unrealistic. This kind of thinking is even celebrated by some start-up founders who want to carry on the legacy of Steve Jobs’ “reality distortion field”—but, as the world saw with Elizabeth Holmes and Theranos, this kind of thinking is dangerous.<sup>27</sup> As Doblin co-founder Larry Keeley wrote, “The dumbest way to simplify a tough problem is to throw out all the hard parts.”<sup>28</sup>

![High Bay Stock Range Warenlager Shelf Shipping by Jens P. Raak](https://statics.bsafes.com/images/papers/token-taxonomy-the-need-for-open-source-standards-around-digital-assets-fig-5.png)

*High Bay Stock Range Warenlager Shelf Shipping by Jens P. Raak (delphinmedia), 2009, used under Pixabay license, accessed 27 Jan. 2020.*

At the same time, however, it’s often the businesspeople who can help programmers bring their technology to the masses. They can recognize market opportunities, secure funding, build businesses, and grow operations to the scale needed to make a dent in the universe. Ron Resnick likened this capability to the business model canvas framework developed by Alex Osterwalder.<sup>29</sup> He said,

> Business model generation is all about speaking the same language. Because what happens even when trying to figure out a business model, you can get mixed up in terminology and verbiage if everybody’s trying to figure something out and they don’t use the same language. 

> In the blockchain context, if you want decentralization, it’s even more important to have some form of common language or a standard to abide by. In decentralization, if you have a whole population of folks who are trying to do business and everybody’s got a different way about doing it, it’s never going to happen.<sup>30</sup>

Both technical and business chops are necessary but insufficient preconditions for commercializing innovative technology; to collaborate, both sides need to communicate on the same terms. That realization was crucial to the first version of the TTF: blockchain was suffering because businesspeople were just making things up and technologists were struggling to take their creations mainstream. Perhaps now, collaboration will be more effective.

### Security and speed
In September 2017, IOTA—then the eighth largest cryptocurrency, with over $1.9 billion market capitalization—was discovered to have a serious vulnerability: an error in its code made it possible to forge signatures and therefore create fraudulent transactions.<sup>31</sup> This mistake was entirely avoidable, had IOTA simply followed SHA-256, the technological standard for hashing.<sup>32</sup> But instead, it broke the “golden rule of cryptographic systems,” according to Neha Narula, director of the Digital Currency Initiative at the MIT Media Lab: “Don’t roll your own crypto.”<sup>33</sup>

The TTF can help projects move quickly and securely, obviating the need to start over from scratch. Re-creating the wheel is a great idea in the early days of a new technology, but it’s not as beneficial when it’s time to scale and ramp up the speed of execution on real, userfacing solutions, and you have good standards like SHA-256 to rely on. For tokens, once we have an audited or formally verified example of a mintable behavior, for instance, there’s no reason to roll your own version. Just plug, play, and continue on to more challenging engineering and business problems once the token elements of your project are locked down.

## Our role in co-creating standards
Whether it’s the TTI or other standards initiatives, such as the Blockchain in Transport Alliance, every domain of expertise needs to shepherd the development and maintenance of standards. If blockchain is normally a team sport, blockchain standards will require an even greater effort to bridge what might otherwise be relationships characterized by some healthy distance, if not overt competition.

### The need for collaboration
The TTF is built on an implicit and explicit ethos of openness: the first specification is hosted on GitHub; the Token Taxonomy Initiative comprises nearly every major enterprise blockchain player; and all of the language is written to suggest it’s an active work in progress rather than a fully formed dictum by the powers that be. In a community that has suffered historically from unnecessary competition (or perceived competition) between Microsoft and IBM or Ethereum and Hyperledger, seeing such entities come together to collaborate openly on a shared standard is a magical thing. It bodes well for the potential for cross-industry collaboration—something that’s necessary given the benefits to security, development, and fundraising that come from scale in the blockchain world.

Joseph Lubin, co-founder of Ethereum and founder of ConsenSys, spoke of the need for decentralized inclusivity: 

> *We set out at the start of Ethereum to be as inclusive as possible, so any person or company that might want to be exposed to the technology should be able to use it. There were certainly some crypto-anarchists in the space broadly who were disgusted that banks might be spoken to or that we, any of us, would educate or collaborate with a bank, let alone a central bank. But if this technology is to have profound impact on the planet, then it needs to be, or it should be, everywhere and widely distributed in terms of different use cases.<sup>34</sup>*

Many stakeholders will need to continuously collaborate to maintain and enhance standards like this. The alternative—taking standards like the TTF and building them as proprietary intellectual property— works in the prototyping and piloting stage, but quickly becomes challenging as projects attempt to scale beyond the brightly colored walls of your organization’s innovation office park.

![Machine Gears by Ryan McGuire, 2015,](https://statics.bsafes.com/images/papers/token-taxonomy-the-need-for-open-source-standards-around-digital-assets-fig-6.png)
*Machine Gears by Ryan McGuire, 2015, used under Gratisography Free Photo License as of 14 Feb 2020.*


### The need for stewardship
Stewardship refers to a community’s responsibility to tend to a shared resource across its life cycle, and being good stewards of the blockchain community will require people to commit to supporting efforts like that of the TTF. 

We at the Blockchain Research Institute have done significant work defining models for blockchain governance and stewardship, and believe that the most robust form of stewardship is the multistakeholder non-state network, consisting of participants from the private sector, government, academia, and civil society at large. For a technology to achieve mass adoption and longevity, such networks must provide stewardship in several areas, such as the development of standards, policy, and knowledge, and the governance of changes to the technology.<sup>35</sup>

For example, the TTI conducted a webinar on token specifications and an overview of the related tools that Microsoft has created, now available on GitHub. The goal of the webinar was to introduce the taxonomy and to encourage builders to use frameworks and tools for experience and automation. Seamless documentation, design, and testing are all things that will let developers focus where they should: on development.

The effort kicked off by this first version of the TTF is meant to be continuous and iterative—and will need to remain as such, if it hopes to succeed in its grand vision.

### The need for certification
As discussed earlier, tokens are only as useful as they are trustworthy. You might argue that your project is “trustless,” but that turn of phrase will only work in the real world if the people listening to you believe what you have to say. 

If you’re Intel in the early 1990s, you can capitalize on the public’s lack of technological understanding and a massive advertising budget to make the world trust computers that have your chips “Inside.” But today, in an environment where Silicon Valley heritage is more cause for skepticism than celebration, things aren’t quite that easy. It is still possible for brands to build themselves up as trustworthy actors—but it is difficult to do so because trust in the digital age is an asymmetric game. (Protect user data 99.99999% of the time, and your reputation will still be in tatters when the one-in-ten-million data breach comes to pass, and the tweet by the one person you’ve disappointed can go viral.) 

In the current business climate, a better bet for building consumer and corporate trust in standards like the TTF is to promote robust, independent, autonomous third-party auditing of technological solutions. Such a third-party auditor can be anyone from the experienced professionals at the Enterprise Ethereum Alliance to the technologically brilliant students at Blockchain@Berkeley, or even a trusted brand like Microsoft. 

Such a validation framework is necessary to build trust in a standard—for otherwise, how will people know which solutions do or do not comply? Without certification programs, it’s easier to “defect” (i.e., claim to follow the standard when you do not) than to “detect” (i.e., spot a faker for what they are). It’s our job to increase the cost of defection and increasing the ease of detection. If we don’t, even our best-laid efforts to define standards around tokens and other pieces of key blockchain infrastructure are doomed to fail.

## Conclusions
Ultimately, there is much work left to be done. The Token Taxonomy Framework is a fantastic base layer, but it won’t solve the significant problems that the blockchain community faces overnight. To achieve its full potential, the TTF will require continued adoption, development, and improvement by a wide variety of actors. 

When standards work, they have a flywheel effect on usage and standardization. Standardization incentivizes investment, investment funds impactful projects, impactful products and services increase protocol usage, and increased protocol usage generates the feedback that the stewards of standards need to improve them over time. Each step of the chain is necessary, and we hope the TTF can achieve the first and last step, thereby making the others much easier to achieve. 

What’s more, the TTF is just one subset of the total standardization that will be necessary for the blockchain world to adopt, and we expect similar such standards to emerge over time. They will emerge within individual protocols (like OpenZeppelin in Ethereum), between protocols (like Cosmos or Interledger), and even between engineering disciplines (e.g., ConsenSys recently released a set of open-source standards for designing decentralized application user experiences).<sup>36</sup> 

The only question now is what will you do. Will you contribute to standardization? If you do, your efforts may be decisive in making decentralization the unshakeable norm for the 2020s and beyond. We’ll be waiting on GitHub. We hope to see you there.

## About the author
Don Tapscott is CEO of the Tapscott Group and executive director of the Blockchain Research Institute and one of the world’s leading authorities on the impact of technology on business and society. He has authored more than 16 books, including *Wikinomics: How Mass Collaboration Changes Everything* (with Anthony Williams), which has been translated into more than 25 languages. Don’s most recent and ambitious book—*Blockchain Revolution: How the Technology Underlying Bitcoin is Changing Money, Business, and the World*—was co-authored with his son, Alex Tapscott, a globally recognized investor, advisor, and speaker on blockchain technology and cryptocurrencies. According to the late Harvard Business School Professor Clay Christensen, *Blockchain Revolution* is “the book, literally, on how to survive and thrive in this next wave of technologydriven disruption.” Don is a member of the Order of Canada and is ranked the second most influential management thinker in the world by *Thinkers50*. He is an adjunct professor at INSEAD and former twoterm chancellor of Trent University in Ontario.

### Acknowledgments
Many thanks to Christian Keil, an operations manager at Astranis Space Technologies, for his substantial contributions to this work. Thanks, too, to Joseph Lubin, co-founder of Ethereum and founder of ConsenSys; Bryce Wells, community director, HACERA, The Unbounded Network; and Jason Pancis, co-founder and chief operating officer, Envision Blockchain Solutions.37 Finally, special thanks to the team at the Token Taxonomy Initiative for their thoughtful feedback and their ongoing stewardship of the token taxonomy:

Marley Gray, Chair, Token Taxonomy Initiative; Principal Architect, Microsoft 

Jonathan Levi, Vice Chair, Token Taxonomy Initiative; CEO, HACERA, The Unbounded Network38 

Paul DiMarzio, Director of Community, Enterprise Ethereum Alliance 

Jack Leahy, Membership Director, Token Taxonomy Initiative 

Ron Resnick, Executive Director, Enterprise Ethereum Alliance 

Brianna Rich, Program Manager, Token Taxonomy Initiative

## About the Blockchain Research Institute
Co-founded in 2017 by Don and Alex Tapscott, the Blockchain Research Institute is an independent, global think tank established to help realize the new promise of the digital economy. For several years now, we have been investigating the transformative and disruptive potential of blockchain technology on business, government, and society. 

Our syndicated research program, which is funded by major corporations and government agencies, aims to fill a large gap in the global understanding of blockchain protocols, applications, and ecosystems and their strategic implications for enterprise leaders, supply chains, and industries. 

Our global team of blockchain experts is dedicated to exploring, understanding, documenting, and informing leaders of the market opportunities and implementation challenges of this nascent technology. Research areas include financial services, manufacturing, retail, energy and resources, technology, media, telecommunications, healthcare, and government as well as the management of organizations, the transformation of the corporation, and the regulation of innovation. We also explore blockchain’s potential role in the Internet of Things, robotics and autonomous machines, artificial intelligence, and other emerging technologies. 

Our findings are initially proprietary to our members and are ultimately released under a Creative Commons license to help achieve our mission. To find out more, please visit www.blockchainresearchinstitute.org.

**Research management**

Don Tapscott – Co-Founder and Executive Chairman
Kirsten Sandberg – Editor-in-Chief
Hilary Carter – Managing Director

**Others in the BRI leadership team**
Alisa Acosta – Director of Education
Luke Bradley – Director of Communications
Wayne Chen – Director of Business Development
Maryantonett Flumian – Director of Client Experience
Roya Hussaini – Director of Administration
Jody Stevens – Director of Finance
Alex Tapscott – Co-Founder

## Notes
<sup>1.</sup> See “Global Leaders Unite to Unveil Comprehensive Framework for Tokenization,” Press Release, Token Taxonomy Initiative, 4 Nov. 2019, for a complete list. tokentaxonomy.org/ global-leaders-unite-to-unveil-comprehensive-framework-for-tokenization, accessed 18 Jan. 2020. 

<sup>2.</sup> *Utility token* is often used to describe a cryptocurrency that represents access and usage rights to the blockchain in development, whereas *security token* is used to describe a cryptocurrency that represents some type of cryptosecurity (i.e., stocks, bonds, or options) in a start-up. See Rajarshi Mitra, “Utility Tokens vs. Security Tokens: Learn the Difference—Ultimate Guide,” Blockgeeks, Blockgeeks Inc., 7 Aug. 2019. blockgeeks. com/guides/utility-tokens-vs-security-tokens/#Utility_Tokens. To exacerbate the head scratching, security tokens also refer to those portable devices used to verify identity or to access electronically controlled resources (e.g., electronic locks to cars or homes). See Christina Majaski, “Understanding Security Tokens,” *Investopedia,* Dotdash, 26 April 2019. www.investopedia.com/terms/s/security-token.asp; and accessed 20 Jan. 2020. 

<sup>3.</sup> Nikhilesh De, “The SEC Just Released Its Long-Awaited Crypto Token Guidance,” *CoinDesk*, Digital Curency Group, 3 April 2019. www.coindesk.com/the-sec-just-releasedits-crypto-token-guidance, accessed 19 Jan. 2020. 

<sup>4.</sup> “What Is ERC-721?” ERC-721, n.d. erc721.org, accessed 19 Jan. 2020. 

<sup>5.</sup> “Collect and Breed Digital Cats!” *CryptoKitties*, Dapper Labs Inc., n.d. www.cryptokitties. co, accessed 19 Jan. 2020. 

<sup>6.</sup> Marley Gray, interviewed via telephone by Christian Keil, 20 Nov. 2019. 

<sup>7.</sup> Doug Bierend, “SpaceX Was Born Because Elon Musk Wanted to Grow Plants on Mars,” *Vice*, Vice Media LLC, 17 July 2014. www.vice.com/en_us/article/jp5g8k/spacex-isbecause-elon-musk-wanted-to-grow-plants-on-mars, accessed 24 Jan. 2020. 

<sup>8.</sup> Mark Kaufman, “When SpaceX Tried to Buy Missiles from Russia: Vodka and a RunAround,” *Inverse*, BDG Media Inc., 2 Aug. 2017. www.inverse.com/article/34976-spacexceo-elon-musk-tried-to-buy-icbm-rockets-from-russia, accessed 24 Jan. 2020. 

<sup>9.</sup> Kevin Rose, “Foundation 20 // Elon Musk,” Video, *YouTube*, Google LLC, 26:42, 7 Sept. 2012. www.youtube.com/watch?v=L-s_3b5fRd8, accessed 24 Jan. 2020. 

<sup>10.</sup> Brandon, “SpaceX: A First Principles Company,” *Digital Initiative,* Harvard Business School, 9 Dec. 2015. digital.hbs.edu/platform-rctom/submission/spacex-a-first-principlescompany, accessed 24 Jan. 2020. 

<sup>11.</sup> Chris Anderson, “Elon Musk's Mission to Mars,” *WIRED*, Condé Nast, 21 Oct. 2012. www.wired.com/2012/10/ff-elon-musk-qa, accessed 25 Jan. 2020. 

<sup>12.</sup> “Global Leaders Unite to Unveil Comprehensive Framework for Tokenization,” Press Release, *TokenTaxonomy.org*, Token Taxonomy Initiative, 4 Nov. 2019. tokentaxonomy. org/global-leaders-unite-to-unveil-comprehensive-framework-for-tokenization, accessed 18 Jan. 2020. 

<sup>13.</sup> Ron Resnick, interviewed via telephone by Christian Keil, 19 Nov. 2019. 

<sup>14.</sup> Paul DiMarzio, interviewed via telephone by Christian Keil, 19 Nov. 2019. 

<sup>15.</sup> Greg McMullen, Primavera De Filippi, and Constance Choi, “Blockchain Identity Services: Technical Benchmark of Existing Blockchain-Based Identity Systems,” foreword by Don Tapscott, Blockchain Research Institute and Coalition of Automated Legal Applications, 30 July 2019. 

<sup>16.</sup> Marley Gray, interviewed via telephone by Christian Keil, 20 Nov. 2019. 

<sup>17.</sup> Gray, interviewed via telephone by Keil, 20 Nov. 2019. 

<sup>18.</sup> As of this writing, one bitcoin was valued at $8,347. CoinMarketCap.com, accessed 25 Jan. 2020. 

<sup>19.</sup> For more on skins (aka outfits) and tokens in Fortnite, see Home of Games, “Unlocking Skins w/ ‘Skin Tokens’ in Fortnite! (Free Honor Guard Skin),” Video, YouTube, Google LLC, 23 Jan. 2019, 00:10:09. www.youtube.com/watch?v=07tLre-JxUI, accessed 25 Jan. 2020. Note it’s a satire. 

<sup>20.</sup> Ron Resnick, interviewed via telephone by Christian Keil, 19 Nov. 2019. 

<sup>21.</sup> Marley Gray, “Token Taxonomy Initiative/Token Taxonomy Framework,” *GitHub*, GitHub Inc., 19 April 2019, last commitment 11 Jan. 2020. github.com/token-taxonomy-initiative/TokenTaxonomyFramework/pulls; for more information on divisible and indivisible, see "Subdividable - > Divisible and Indivisible," GitHub.com/token-taxonomy-initiative/TokenTaxonomyFramework/commit/7a847eb869de4c56a0bb64ee877e8603c9e1ae64#diff-04c6e90faac2675aa89e2176d2eec7d8, accessed 11 Jan. 2020.

<sup>22.</sup> Julio Faura and Daniel Lehrner, “Emoney,” *TokenTaxonomy.org*, Token Taxonomy Initiative, 23 Oct. 2019. tokentaxonomy.org/wp-content/uploads/2019/10/Emoney-spec.pdf, accessed 19 Jan. 2020. Note this link triggers an automatic download. 

<sup>23.</sup> Token Taxonomy Framework Draft Specification Library, *TokenTaxonomy.org*, Token Taxonomy Initiative, n.d. tokentaxonomy.org/framework-draft-specification-library, accessed 19 Jan. 2020. 

<sup>24.</sup> WYSIWIG is short for “what you see is what you get.” 

<sup>25.</sup> Marley Gray, interviewed via telephone by Christian Keil, 20 Nov. 2019. 

<sup>26.</sup> Gray, interviewed via telephone by Keil, 20 Nov. 2019. 

<sup>27.</sup> Alexis C. Madrigal, “The Steve Jobs 'Reality Distortion Field' Even Makes It Into His FBI File,” *The Atlantic*, Atlantic Media Company, 9 Feb. 2012. www.theatlantic.com/ technology/archive/2012/02/the-steve-jobs-reality-distortion-field-even-makes-it-intohis-fbi-file/252832; and Lisa de Moraes, “‘The Inventor: Out for Blood in Silicon Valley’ Documents ‘Reality Distortion Field’ Elizabeth Holmes Sucked People Into,” *Deadline*, Penske Business Media LLC, 8 Feb. 2019. deadline.com/2019/02/elizabeth-holmestheranos-alex-gibney-inventor-out-for-blood-silicon-valley-hbo-tca-1202553096, both accessed 24 Jan. 2020. 

<sup>28.</sup> Larry Keeley et al., *Ten Types of Innovation: The Discipline of Building Breakthroughs *(San Francisco: O'Reilly Media, April 2013). www.oreilly.com/library/view/ten-typesof/9781118571392, accessed 19 Jan. 2020. 

<sup>29.</sup> Ted Greenwald, “Business Model Canvas: A Simple Tool for Designing Innovative Business Models,” *Forbes*, Forbes Media LLC, 31 Jan. 2012. www.forbes.com/sites/ tedgreenwald/2012/01/31/business-model-canvas-a-simple-tool-for-designinginnovative-business-models/#66a7507a16a7, accessed 24 Jan. 2020. 

<sup>30.</sup> Ron Resnick, interviewed via telephone by Christian Keil, 19 Nov. 2019. 

<sup>31.</sup> While IOTA doesn’t technically use a blockchain, it is well within the family of decentralized technologies and therefore the scope of this paper. Its innovation—the directed acyclic graph that IOTA calls a tangle—can be understood as an alternative structure to the consensus layer. See Neha Narula, “Cryptographic Vulnerabilities in IOTA,” *Medium*, Medium Company, 7 Sept. 2017. medium.com/@neha/cryptographicvulnerabilities-in-iota-9a6a9ddc4367, accessed 19 Jan. 2020. 

<sup>32.</sup> Raul Jordan, “The State of Hashing Algorithms: The Why, the How, and the Future,” *Medium*, Medium Company, 23 July 2018. medium.com/@rauljordan/the-state-of-hashingalgorithms-the-why-the-how-and-the-future-b21d5c0440de, accessed 24 Jan. 2020. 

<sup>33.</sup> Neha Narula, “Cryptographic Vulnerabilities in IOTA,” *Medium*, Medium Company, 7 Sept. 2017. medium.com/@neha/cryptographic-vulnerabilities-in-iota-9a6a9ddc4367, accessed 19 Jan. 2020. 

<sup>34.</sup> Joseph Lubin, interviewed via telephone by Don Tapscott, 3 May 2017. 

<sup>35.</sup> Don Tapscott and Alex Tapscott, “Realizing the Potential of Blockchain: A Multistakeholder Approach to the Stewardship of Blockchain and Cryptocurrencies,” *WEForum.org*, World Economic Forum, 5 July 2017. www.weforum.org/agenda/2017/07/blockchain-the-ledgerthat-will-record-everything-of-value, accessed 20 Jan. 2020. 

<sup>36.</sup> OpenZeppelin Contracts, *GitHub*, n.d. github.com/OpenZeppelin/openzeppelin-contracts; Cosmos Network, n.d. cosmos.network; Interledger, n.d. Interledger, n.d. interledger. org; and ConsenSys Design, ConsenSys Inc., n.d. consensys.design/design-system, all accessed 20 Jan. 2020. 

<sup>37.</sup> Quotations by Jason Pancis on pages 16 and 17 came from an e-mail exchange among Pancis, Don Tapscott, and Kirsten Sandberg, 14 Feb. 2020. 

<sup>38.</sup> Quotations by Jonathan Levi on pages 9 and 15 came from an e-mail exchange among Levi, Bryce Wells, Don Tapscott, and Kirsten Sandberg, 14 Feb. 2020.


</div>

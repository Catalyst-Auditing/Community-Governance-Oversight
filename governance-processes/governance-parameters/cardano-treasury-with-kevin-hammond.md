---
description: >-
  A Catalyst Town Hall Presentation on the Cardano Treasury with an After Town
  Hall Q&A
---

# Cardano Treasury with Kevin Hammond

## Catalyst Town Hall Presentation

At a Catalyst Town Hall of April 20th 2022, [Kevin Hammond](https://iohk.io/en/team/kevin-hammond) an IOHK Technology manager supported by [Jared Corduan](https://iohk.io/en/team/jared-corduan) an IOHK Software Engineering gave a presentation on the Cardano Treasury.

{% embed url="https://youtu.be/ppM_ogWPcJw?t=3526" %}

## Slides

![](<../../.gitbook/assets/Screenshot 2022-05-08 180746.png>)

### What is the Cardano Treasury ?

[59:37](https://youtu.be/ppM\_ogWPcJw?t=3577)

![](<../../.gitbook/assets/Screenshot 2022-05-08 180913.png>)

### Treasury Growth

[1:00:12](https://youtu.be/ppM\_ogWPcJw?t=3612)

The Treasury has healthy growth from the Shelley to the Alonzo eras. This is important because the Treasury is a war chest to help fund work we need to do on Cardano. Its there to make things happen.

![](<../../.gitbook/assets/Screenshot 2022-05-08 181222.png>)

### How is the Treasury Funded ?

[1:00:53](https://youtu.be/ppM\_ogWPcJw?t=3653)

We are currently at about 800 million ADA. This comes from two places

1\) monetary expansion from the Cardano reserves. The Cardano reserve is a fixed amount of ADA put aside when blockchain created which is gradually being burnt down to expand the treasury.

2\) blockchain fees to process transactions

The proportion of the treasury funded from blockchain fees rather than from Cardano reserves will increase over time. There is also the unspent treasury carried forward from the previous period. The temporal units in Cardano are Epochs. Which means the treasury gets topped up evrey Epoch by expansion from the reserves and fees.

![](<../../.gitbook/assets/Screenshot 2022-05-08 183923.png>)

### Rewards distribution

[1:02:07](https://youtu.be/ppM\_ogWPcJw?t=3727)

How are the rewards calculated ? What happens is that the reserves and the fees are put into a rewards pot. This is distributed in two ways -

1\) 80% goes into Pool rewards distributed via charges to each Stake Pool and given out as User Rewards.

2\) 20% goes into the Treasury.

![](<../../.gitbook/assets/Screenshot 2022-05-08 215727.png>)

### What is the Treasury used for ?

[1:02:55](https://youtu.be/ppM\_ogWPcJw?t=3775)

**Catalyst Projects** - supporting the Cardano Ecosystem.

**Core Cardano Development** - we will need to start dipping into Treasury to fund Core Cardano Development. At present IO is funding all the development on Cardano but this will change to come from Treasury and allocated to various developers to propel things forward.

In addition there are Governance and System Managements costs. And scope for charitable or academic funding.

![](<../../.gitbook/assets/Screenshot 2022-05-08 221637.png>)

### How are Funds Allocated ?

[1:04:20](https://youtu.be/ppM\_ogWPcJw?t=3860)

How are our decisions taken ?

At present we have voting on the Catalyst Sidechain. Votes are automatically tallied in an extensive process.

Then there are a series of audit checks and validations to make sure the funds will be dispersed as expected.

Having gone through the audit checks and validation we prepare a funding plan. This is passed onto our DevOps team who prepare a number of MIR transactions (MIR = central fund transfer).

The MIR transactions are signed by a set of 7 governance keys. Then the proposal funds are submitted on the mainnet.

![](<../../.gitbook/assets/Screenshot 2022-05-08 220526.png>)

### Central Funds Transfers (MIRS)

[1:06:32](https://youtu.be/ppM\_ogWPcJw?t=3992)

A central fund transfer can work in two ways -

1\) A transfer between treasury and the reserves. These are periodic accounting moves made to balance the books. Analougous to central bank transactions.

2\) The MIR transactions transfer funds to a series of rewards addresses. A single MIR transaction can transfer funds to 300 reward addresses.

![](<../../.gitbook/assets/Screenshot 2022-05-09 002016.png>)

## After Town Hall - Q\&A

{% embed url="https://youtu.be/yG0lifQOaFk" %}

## Overview

At an Catalyst After Town Hall of April 20th 2022, [Kevin Hammond](https://iohk.io/en/team/kevin-hammond) an IOHK Technology manager and [Jared Corduan](https://iohk.io/en/team/jared-corduan) an IOHK Software Engineering Lead answered questions about the Cardano Treasury.

### Kevin Hammond

> Kevin Hammond is a technology manager at IOHK. He has 35 years of experience in functional programming. He was a member of the Haskell Committee, produced the first Haskell compiler implementation at Glasgow University, and worked on the design and implementation of the Glasgow Haskell compiler. Kevin has produced more than 130 research publications and established an excellent reputation for his work on functional programming, types and resource analysis. He has worked for IOHK since 2019, and has been a key member of the formal methods and Cardano delivery teams.

### Jared Corduan

> Jared Corduan is a mathematician with interests in logic and computer science. He holds a PhD in mathematical logic from Dartmouth College, where he studied reverse mathematics, computability theory, infinitary combinatorics, and forcing. He is fascinated by the incompleteness phenomenon. Jared worked as an industrial programmer from 2011, both in finance and in healthcare technology, before joining IOHK in 2018. He is most excited when he gets to work on projects that combine his love of mathematics and programming.

## Questions

### Is there a Treasury Address ? How can it be queried ?

0:51 - Is there a Treasury Address ? How can it be queried ? - Filip

> On Cardano we have addresses that are controlled by private and public keys. So Treasury has some sort of multi SIG functionality. But I've never seen a treasury address. Is it an address? Can we query it somewhere? - Filip

01:28 - Jared Corduan

> Its not an address in the usual sense. All 45 billion ADA are a part of one of what I like to call the six pots of ADA.

> The reserves in the treasury are two of those pots of ADA.

> Even though they're not technically an address, they don't show up in the UTXO set, they are not one of the unspent transaction outputs.

> There are special rules that govern it. In order to draw from the treasury, it does require quorum many signatures from the governance nodes.

> You can query the balance, if you have a running Node, there is a command line utility or Cardano. CLI that you can get the balance of the Treasury and the reserves at any time.

### Who is making the governance decisions ?

02:51 - Who is making the governance decisions ? - Allison

> Who is in charge of that process that you laid out? Not from a technical standpoint, but from a making a decision? Who holds the governance keys ? What audit steps are necessary? What documentation is required ?

> Where are these funds considered to be legally domiciled ? So if I'm running a business and getting funds, where is my counterparty located? Who is doing customer due diligence typical of a business that's dispersing funds ?

04:13 - Kevin Hammond

> In terms of the decision making process, we're evolving. At the moment we're transitioning from the bootstrapping process where IOG has had de facto control over the system using authority delegated to it by the Cardano Foundation to one where we will have an open governance system.

> I don't know exactly at this point of time how that open governance system is going to work out. So you need to stay tuned to this. But the intention is very much that IO will be part of the process but not controlling the process.

05:13 - Jared Corduan

> There are seven keys. IO has three, Emurgo has two and Cardano Foundation has two and the quorum is five.

05:34 - Filip

> Just delegated from CF to IOG. So IOG basically handles five.

05:48 - Kevin Hammond

> Yes. I know for a fact that the delegation at the moment is to IOG staff who are very carefully vetted and follow very strict security and operational process. This is the de facto rather than de jure position.

### Who decided that it's a five of seven quorum ?

06:25 - Allison

> I do come at this as in a position of being very appreciative of the work IOG is doing to move towards true Decentralized Governance. My questions are more as a business person trying to understand the status quo. So I can answer some questions for my accountant and satisfy my intellectual curiosity.

> Using this example of the keys. Who decided that it's a five of seven quorum ?

07:15 - Kevin Hammond

> It was a decision taken very early in the existence of the blockchain. So I imagine that was taken at the meeting where the blockchain was was set up.

07:31 - Jared

> Yeah, it goes back to Byron, it goes back to the very, very, very beginning.

### Where are the funds domiciled ?

07:39 - Kevin Hammond

> As to the question where are the funds domiciled ? I would need to I need to pass that onto the legal team to give you your correct answer.

08:09 - Jared

> Yeah I don't think they are \[domiciled].

08:12 - Allison

> And I believe that as well. It's just very interesting to fit that into legacy processes

08:20 - Kevin Hammond

> It is extremely interesting how this fits into legacy processes. Regulators and national authorities are becoming aware of the existence of blockchains and cryptocurrencies and are starting to evolve legislation. So what we can expect is that there will be changes in this area. What Cardano is doing is to make itself as decentralized as possible. The goal is very much not for there to be a central authority for Cardano.

09:46 - Jared

> I doubt this is unique to Cardano. If you mint a block in Bitcoin, what country gives you the authority? What entity gives you authority to mint that?

10:05 - Allison

> It's a question everybody has to answer from miners to stake pools. I mean, do I have to report on my staking rewards? It's an industry wide question.

10:20 - Kevin Hammond

> The position in the UK is that they don't care where the cryptocurrency is domiciled if you make a profit, you get taxed on it.

### Who's doing the due diligence around the release of funds?

10:33 - Allison

> Who's doing the due diligence around the release of funds? Not from a technical standpoint, but from a regulatory standpoint?

10:57 - Kevin Hammond

> I'll pass it on to the legal team. They will give you the proper answer to that.

### What do you see as the evolution of the 7 keys ?

11:10 - George Lovegrove

> What do you see as the evolution of the 7 keys ? Do you see it going through a number,like 11 ? Or is it going to be like a big transition to a democratic system and those governance keys become a separate thing? How are you going to see that changing over time?

11:36 - Kevin Hammond

> It's going to depend on how the system evolves. We anticipate the number increasing. We can't say exactly how many it will increase to.

> I would still discussing that with Harris, governance team and with the Cardano foundation.

> It's going to have to increase to meet the structures that are set up and and over time. The numbers could vary. It depends a lot on where we end up with the governance structures.

> What we like is having a prime number. We need an odd number, so that we don't have problems with splits in decision making. What we like is for there to be a substantial quorum. And ideally, again, a prime number

### Could the governance keys be represented by a separate kind of contract or democracy ?

12:33 - George Lovegrove

> For instance, to represent some kind of persons of understanding or capacity. Could that governance then be delegated from to a sub democracy ? So kind of so you layer it? Is that Is that something that's of any consideration or any any thought?

13:02 - Kevin Hammond

> The governance keys are the ones that are controlling the decisions as we move forward?

> These are public keys. And the public keys could be owned by any entity. The question is going to be what is a legitimate entity?

> Should they always be owned by individuals? Should they be owned by groups of individuals? What the right was the right structure? We don't at this point, have the answer to that.

> We're going to find that out pretty soon, I think. So stay stay posted. So apologies. I'm being a bit cagey here. But the whole thing is in transition, and we're evolving it we're designing it. There are lots of negotiations going on. So I can't I can't say for sure.

> But I would imagine that the initial holders of government's case would be would be individuals rather than organizations or other entities. There's no reason in principle why you couldn't have an entity.

So the public keys could be could be representative.

### Is there a number that sets Treasury distribution between Catalyst, Core Development and Governance costs ?

[14:23](https://youtu.be/yG0lifQOaFk?t=863) - George Ramayya

From the Treasury standpoint, when you look at foundations and the cost structure, there is always the number between six to eight persons. Is that number defined for this treasury too? And when we look at the division of the Treasury distributed out to the Catalyst project, Core Development or governance costs  is there a number to show the division between them?&#x20;

15:11 - Kevin Hammond

No, there is no defined number. This is something that needs to be agreed as part of the governance process.

As you can imagine the split between the different activities could vary depending on need.

The operating costs for some parts of the blockchain are going to be fixed. But that might change over time.&#x20;

But it's not going to be constant over time, particularly because the costs we are incurring are in fiat and the Treasury is denominated in ADA.

In terms of the split between Catalyst projects, Core Development. That is going to depend on the agreement between it and the governance body.

And I imagine some of those discussions are going to be quite heated, because people always want to spend on one thing rather than another.&#x20;

But the reality is that you've got to spend enough on the Cardano core development. If you don't spend on the core development, there isn't going to be a blockchain or it's not going to evolve, it's not going to do what people want. So there's going to be some level of spend that you have to incur there.&#x20;

And then the ecosystem spend will be doing exciting things beyond the core of the development. I can't give you a percentage or guess what I think the percentages are.&#x20;

17:42 - Kevin Hammond

Part of governance processes precisely is to define what is the executive split? What should be the spend on each of the different parts that make up Cardano?

### Have you had situations to date where you've needed to reach a quorum?

[18:11](https://youtu.be/yG0lifQOaFk?t=1092) - Jonathan

Have you had situations to date where you've needed to reach a quorum? Where you've actually tried to make decisions, and there hasn't been an agreement ? Just think about topics that might come up as we go down to distributing this decision?

18:36 - Kevin Hammond

Every decision is discussed in detail. Every change that's being made to the Cardano parameters.

This is subject of hot debate, within Cardano. Its informed within IO, within the Cardano Foundation. It's informed by lots of information about how the blockchain is operating. It's informed by research that's going on.

We can't reveal all of that which is frustrating to us, because you can see the community saying, oh, you should do this. And you should do that. And we're thinking well, yes, we agree. We know exactly where you're coming from. But guys, we can't. We can't tell you why we can't.

19:40 - Kevin Hammond

We're starting to make changes to some of the operating parameters. It's taken a while to get to that position, not because we've not wanted to, but because we have to get the system up and running in a stable way.

And what we've been able to start increasing things like block sizes, etc.

We're also starting to debate some of the other parameters. There is a survey gone out about things like the minimum cost, the minimum pool cost. We are taking that into account. Lots of debate going on.

The great thing is that we're starting to get to a stage where there's alignment on how we should be proceeding.

So you will see lots of things happening over the coming months as we go to the transition. And the goal is to establish process and to establish mechanisms. So that although everything is properly scrutinized, all opinions are taken into account, we'll have a process that allows us to keep moving forwards as we go to Voltaire, as we move towards an open governance system.

21:03 - Kevin Hammond

And you'll start to see more transparency. We're setting up mechanisms where we're recording the reasons & rationale for the decisions and are planning explanations for why decisions being taken.

One or two of the decisions we can't tell you why we've made them because we might reveal something about some part of blockchain security.

### Decision making in respect of Core Development

[21:43](https://youtu.be/yG0lifQOaFk?t=1303) - Phil Khoo

You've mentioned Core Development of the Cardano blockchain. How would the decision making of that be undertaken?

21:53 - Kevin Hammond

This is being defined at the moment. Decisions about the current environment are going to be informed by community needs and by community decisions.

What we've had to do to date is to follow the path we'd set out with Cardano Foundation several years ago. A set of things that IOG agreed with Cardano Foundation. We will do these things, we will deliver them.

And we're going through a process at the moment called "Get Cardano done". So we are in a position where we're handing off.

I was talking earlier today with [Vito Silva](https://iohk.io/en/team/vitor-silva). He is the Product manager for Cardano. What he is doing at the moment is to sift through the CIP ([Cardano Improvement Proposals](https://cips.cardano.org)).

So this \[CIP] process where ideas are being surfaced by the community has some very good ideas coming up. We're cognizant of these but we haven't been able to take all of them forward yet simply because the normal pipeline for doing things is so full.

### &#x20;Is IOG simply going to hang on and keep spending until this whole governance system is in place ?

[23:45](https://www.youtube.com/watch?v=yG0lifQOaFk\&t=1425s) - Steven

I'm very aware of the extraordinary expense that IOG has borne and is continuing to bear. At some point the Treasury will have to begin to bear that. Is IOG simply going to hang on and keep spending until this whole governance system is in place and vetted, functional and 100% blissfully glorious, or is there something else that we should know?

24:30 - Kevin Hammond

You're asking me here a question about IOG's company's strategy ? The reality is there has to come a point when IOG stop spending its money because it's a profit making company. It has to get a return on the money that's been spent.&#x20;

The Treasury has been it's been built up. You've seen the good level of Treasury. It's building up, which is great, we are going to have to start dipping into that.

It is very expensive to develop and maintain blockchains, particularly to very high standards.

There's going to be a transition at some point. How this develops in terms of who pays for what, because IOG will always have some things that IOG wants to do.

## References

### Cardano Improvement Proposals (CIPs) <a href="#cardanoimprovementproposalscips" id="cardanoimprovementproposalscips"></a>

{% embed url="https://cips.cardano.org" %}

Cardano Improvement Proposals (CIPs) describe standards, processes; or provide general guidelines or information to the Cardano Community. It is a formal, technical communication process that exists off-chain. CIPs do **not** represent a commitment of any form towards existing projects. Rather, they are a collection of sensible and sound solutions to common problems within the Cardano ecosystem.

### [Understanding the Extended UTXO model](https://docs.cardano.org/plutus/eutxo-explainer)

Cardano (like Bitcoin) is an Unspent Transaction Output (UTXO)-based blockchain, which utilizes a different accounting model for its ledger from other account-based blockchains like Ethereum. Cardano implements an innovative [Extended Unspent Transaction Output (EUTXO) model](https://iohk.io/en/blog/posts/2021/03/11/cardanos-extended-utxo-accounting-model/), which is introduced by the Alonzo upgrade to support multi-assets and smart contracts.

### Vitor Silva, Product Manager Operations

{% embed url="https://iohk.io/en/team/vitor-silva" %}

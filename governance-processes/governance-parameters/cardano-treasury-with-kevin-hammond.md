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

As to the question where are the funds domiciled ? I would need to I need to pass that onto the legal team to give you your correct answer.

08:09 - Jared&#x20;

Yeah I don't think they are \[domiciled].

08:12 - Allison

And I believe that as well. It's just very interesting to fit that into legacy processes

08:20 - Kevin Hammond

It is extremely interesting how this fits into legacy processes. Regulators and national authorities are becoming aware of the existence of blockchains and cryptocurrencies and are starting to evolve legislation. So what we can expect is that there will be changes in this area. What Cardano is doing is to make itself as decentralized as possible. The goal is very much not for there to be a central authority for Cardano.

09:46 - Jared

I doubt this is unique to Cardano. If you mint a block in Bitcoin, what country gives you the authority? What entity gives you authority to mint that?

10:05 - Allison

It's a question everybody has to answer from miners to stake pools. I mean, do I have to report on my staking rewards? It's an industry wide question.

10:20 - Kevin Hammond

The position in the UK is that they don't care where the cryptocurrency is domiciled if you make a profit, you get taxed on it.

### Who's doing the due diligence around the release of funds?

10:33 - Allison

Who's doing the due diligence around the release of funds? Not from a technical standpoint, but from a regulatory standpoint?

10:57 - Kevin Hammond

I'll pass it on to the legal team. They will give you the proper answer to that.

### What do you see as the evolution of the 7 keys ?

11:10 - George Lovegrove

What do you see as the evolution of the 7 keys ? Do you see it going through a number,like 11 ? Or is it going to be like a big transition to  a democratic system and those governance keys become a separate thing? How are you going to see that changing over time?

11:36 - Kevin Hammond

It's going to depend on how the system evolves. We anticipate the number increasing. We can't say exactly how many it will increase to.

I would still discussing that with Harris, governance team and with the Cardano foundation.&#x20;

It's going to have to increase to meet the structures that are set up and and over time. The numbers could vary. It depends a lot on where we end up with the governance structures.

What we like is having a prime number. We need an odd number, so that we don't have problems with splits in decision making. What we like is for there to be a substantial quorum. And ideally, again, a prime number

## References

### [Understanding the Extended UTXO model](https://docs.cardano.org/plutus/eutxo-explainer)

Cardano (like Bitcoin) is an Unspent Transaction Output (UTXO)-based blockchain, which utilizes a different accounting model for its ledger from other account-based blockchains like Ethereum. Cardano implements an innovative [Extended Unspent Transaction Output (EUTXO) model](https://iohk.io/en/blog/posts/2021/03/11/cardanos-extended-utxo-accounting-model/), which is introduced by the Alonzo upgrade to support multi-assets and smart contracts.

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

I don't know exactly at this point of time how that open governance system is going to work out. So you need to stay tuned to this.

## References

### [Understanding the Extended UTXO model](https://docs.cardano.org/plutus/eutxo-explainer)

Cardano (like Bitcoin) is an Unspent Transaction Output (UTXO)-based blockchain, which utilizes a different accounting model for its ledger from other account-based blockchains like Ethereum. Cardano implements an innovative [Extended Unspent Transaction Output (EUTXO) model](https://iohk.io/en/blog/posts/2021/03/11/cardanos-extended-utxo-accounting-model/), which is introduced by the Alonzo upgrade to support multi-assets and smart contracts.

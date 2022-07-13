---
description: Meeting 2 - Fund 8 - dRep White Paper Working Group Meeting
---

# Meeting - 5th July 2022

## Attendees

|                     |                                                                   |
| ------------------- | ----------------------------------------------------------------- |
| Aharon Porath       | Consenz                                                           |
| Kenric Nelson       | [Photrek](https://photrek.world/)                                 |
| Steph Macurdy       | [Wolfram Blockchain Labs](https://www.wolframblockchainlabs.com/) |
| Stephen Whitenstall | [QADAO](https://quality-assurance-dao.github.io/)                 |
| Thorsten Pottebaum  | adanamics ([linktree](https://linktr.ee/adanamics))               |

### Apologies

|                |                                             |
| -------------- | ------------------------------------------- |
| George Ramayya |                                             |
| Frank Albanese | [Snapbrilla](https://www.snapbrillia.com/)  |
| Philip Lazos   | [IOG](https://iohk.io/jp/team/philip-lazos) |

## Information

#### Community Governance Group

[https://quality-assurance-dao.gitbook.io/community-governance-oversight/](https://quality-assurance-dao.gitbook.io/community-governance-oversight/)

Documentation funded by [Fund 7 - QA-DAO Transcription Service](https://cardano.ideascale.com/c/idea/383492)

#### Meeting GitHub Task

https://github.com/Catalyst-Auditing/Community-Governance-Oversight-Coordination/issues/71

## Agenda



## Brief Updates

[00:25](https://youtu.be/WRC1n05tIr4?t=25)

{% hint style="info" %}
Brief Updates/Notices from each participant - All
{% endhint %}

Kenric Nelson - [00:37](https://youtu.be/WRC1n05tIr4?t=37)

Steph Macurdy- [01:14](https://youtu.be/WRC1n05tIr4?t=74)

Aharon Porath - [01:35](https://youtu.be/WRC1n05tIr4?t=95)

Thorsten Pottebaum - [02:10](https://youtu.be/WRC1n05tIr4?t=130)

Stephen Whitenstall - [02:37](https://youtu.be/WRC1n05tIr4?t=157)

## Research Budget  <a href="#docs-internal-guid-46e3b976-7fff-5747-352b-2a19fb0d689f" id="docs-internal-guid-46e3b976-7fff-5747-352b-2a19fb0d689f"></a>

[03:02](https://youtu.be/WRC1n05tIr4?t=182)

{% hint style="info" %}
Any Budget updates or issues ? - Kenric Nelson
{% endhint %}

Project Start - 1st June 2022. End - 30th September 2022

Small amount reserved for community members&#x20;

Thorsten to recruit reviewers - August 2022

## Research Project Planning <a href="#docs-internal-guid-4f8b919c-7fff-cd39-7ed8-6153f4c1e729" id="docs-internal-guid-4f8b919c-7fff-cd39-7ed8-6153f4c1e729"></a>

[03:58](https://youtu.be/WRC1n05tIr4?t=238)

{% hint style="info" %}
Any updates on Project Plan timetable and deliverables - Stephen Whitenstall
{% endhint %}

No updates

## Whitepaper <a href="#docs-internal-guid-c31ad56f-7fff-35c4-1333-f53118198988" id="docs-internal-guid-c31ad56f-7fff-35c4-1333-f53118198988"></a>

{% hint style="info" %}
Please prepare Detailed Outline of your section for next meeting - All
{% endhint %}

### The role of Delegated Representation in Blockchain Governance

Philip Lazos

[04:27](https://youtu.be/WRC1n05tIr4?t=277)

{% hint style="info" %}
Email follow-up - apologies sent
{% endhint %}

### Forming consensus in governance documentation <a href="#docs-internal-guid-b92c864e-7fff-c672-1030-52cc4e0213c7" id="docs-internal-guid-b92c864e-7fff-c672-1030-52cc4e0213c7"></a>

Aharon Porath, Kenric Nelson

[04:43](https://youtu.be/WRC1n05tIr4?t=283)\


How different building blocks will work together. How fits into Consenz platform. Liquid democracy is the main component. But also references direct democracy. Will be discussed further in Consenz meetings. - Aharon\


If you prefer to work in your own document can you provide a link in the main White paper document ? In August 2022 we will open up to reviewers and then the public at large. - Kenric

Will we use an academic peer review process ? - Aharon

The White paper approach is editor based and community reviewed. It will be formatted as an academic paper. At the end of this process we will decide on whether to submit to a journal. A Follow-on proposal in Fund 10 is possible for a peer reviewed process. In general I see the academic research process spanning 3 years. - Kenric

What do you mean by original results ? - Aharon

Our goal for this project is to define the measurements and to start building the tools to monitor the process of decentralized decision making and to monitor the outcomes of that. How good are the decisions and do they produce a strong ecosystem? - Kenric

Those are the things we really should be focused on. You are doing that Aaron by documenting the processes that go into producing high quality documents as a community. - Kenric

### Measuring Voting Power in a Delegated Representative Process&#x20;

Steph Macurdy

[15:39](https://youtu.be/WRC1n05tIr4?t=939)

An original result would be to calculate the Banzhof Power Index for the Catalyst community.&#x20;

That is a big goal, because defining the processes of how Catalyst works into a formula for calculating the power index has subjectivity built into it.

How do we define the rules and parameters of what constitutes a voter and how do we get that data?&#x20;

I met with a Wolfram expert on the function that outputs coalitions or entities. - Steph.

### Simplification strategies

[17:24](https://youtu.be/WRC1n05tIr4?t=1044)

But what we could do is take some simple examples.&#x20;

Kenric brought up the \[Genesis] key ownership between IOG, Emurgo and the Cardano Foundation as a simple example. Because there's three entities and seven total votes. How do we define what the power index is within that group? - Steph

{% hint style="info" %}
Kenric and Steph to talk through the Banzhof process of simplification - treat each wallet cohort as a single voting block.
{% endhint %}

[17:59](https://youtu.be/WRC1n05tIr4?t=1079)

I've given you access to the data we have from Funds 3 through 6. It is probably good to just talk through it. - Kenric&#x20;

I think the first step is some simplifications.&#x20;

Where we treat each wealth cohort, wallets with between 500 and 5,000 and then between 5000 and 50,000, etc, going out as a single voting bloc. That way, there's not as many players and the computational calculations are dramatically reduced.&#x20;

&#x20;Steph - to give us synthetic data - to see if we have any dramatic swings in power

I have a function that is close - there is a Wolfram review process - but need to improvise myself&#x20;

Thorsten - data vote per proposal

Kenric - possible in some Fund data but not all and is immense

Thorsten - level of impact of biggest wallets can be indicative - of Dictator type situations - eg top 20 etc

Kenric - even without mapping - you can do empirical analysis of the vote results - and infer ? Look at percent times it when from winning proposal

Sometimes close votes can be swayed by small wallets

&#x20; Interesting in case of dRep wallets in one or other section - of concentration of voting power and where the borde

\
During Macurdy’s update, it would be good to discuss the example of the [7 genesis keys created at the formation of the Cardano network](https://docs.google.com/document/d/1pv56vbmACxknehy04Dgc03RwvIMcyMjdHxlvNN9AOZc/edit).

## References

### Voting Power of Cardano’s Genesis Keys <a href="#docs-internal-guid-6c8cd2f8-7fff-c15a-4ec5-69d4863ea631" id="docs-internal-guid-6c8cd2f8-7fff-c15a-4ec5-69d4863ea631"></a>

by Kenric Nelson

{% hint style="info" %}
[Original document link](https://docs.google.com/document/d/1pv56vbmACxknehy04Dgc03RwvIMcyMjdHxlvNN9AOZc/edit?usp=sharing)
{% endhint %}

When Cardano was initially set up, there were 7 genesis keys established that are still used for CIP changes and Hard Fork Combinators. Initially, they were distributed 3 IOHK, 2 Cardano Foundation, and 2 Emurgo. A vote of 5 is needed to approve a change. Most people’s intuition is that IOHK’s 3/7 votes is only a slight advantage. In fact, this is enough to establish veto power.&#x20;

&#x20;Using the [Banzhaf Power Index website](http://people.math.binghamton.edu/fer/courses/math130/ZIS\_Spr14/chapter1/Banzhaf.html), one can compute the percentage of decisive votes for each party. As shown in Figure 1, IOHK is critical in 3 of 5 instances. A critical vote refers to a winning coalition in which dropping that vote would cause the coalition to lose. CF and Emurgo each have 1 of 5 critical votes. Thus IOG has a 60% power index compared with its 43% number of votes. CF and Emurgo only have 20% power despite 28.5% of the votes. The subtlety of this nonlinear power relationship is an excellent example of how savvy players can set up systems that appear equable but actually have quite distorted power relationships.&#x20;

![](<../.gitbook/assets/Screenshot 2022-07-13 140653.png>)

Currently, at least one of the weaker parties (CF or Emurgo) is reported to have delegated their genesis keys to IOHK. This gives IOHK the 5 keys necessary to be a dictator regarding the CIP and Hard For Combinator updates. While the goal is to transition during Voltaire to a member-based organization that manages the genesis keys, this example demonstrates how a slight advantage in the voting ratio can lead to a substantial advantage in voting power. And an early advantage in voting power can be used over time to further increase this disparity.&#x20;

This example provides a power illustration of the importance of monitoring and controlling the distribution of Banzhaf voting power in the Cardano community processes.

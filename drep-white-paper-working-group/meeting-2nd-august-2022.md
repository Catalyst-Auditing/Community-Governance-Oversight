---
description: Meeting 4 - Fund 8 - dRep White Paper Working Group Meeting
cover: ../.gitbook/assets/Screenshot from 2022-08-15 20-37-36.png
coverY: 0
---

# Meeting - 2nd August 2022

## Attendees

|                     |                                                                   |
| ------------------- | ----------------------------------------------------------------- |
| Kenric Nelson       | [Photrek](https://photrek.world/)                                 |
| Steph Macurdy       | [Wolfram Blockchain Labs](https://www.wolframblockchainlabs.com/) |
| Stephen Whitenstall | [QADAO](https://quality-assurance-dao.github.io/)                 |

### Apologies

|                    |                                                     |
| ------------------ | --------------------------------------------------- |
| Aharon Porath      | Consenz                                             |
| Philip Lazos       | [IOG](https://iohk.io/jp/team/philip-lazos)         |
| Thorsten Pottebaum | adanamics ([linktree](https://linktr.ee/adanamics)) |

## Information

#### Community Governance Oversight Group

{% hint style="info" %}
[https://quality-assurance-dao.gitbook.io/community-governance-oversight/](https://quality-assurance-dao.gitbook.io/community-governance-oversight/)
{% endhint %}

{% hint style="info" %}
Documentation funded by [Fund 7 - QA-DAO Transcription Service](https://cardano.ideascale.com/c/idea/383492)
{% endhint %}

#### Meeting GitHub Task

(Used for Project Management tracking and reporting)

{% hint style="info" %}
[https://github.com/Catalyst-Auditing/Community-Governance-Oversight-Coordination/issues/96](https://github.com/Catalyst-Auditing/Community-Governance-Oversight-Coordination/issues/96)
{% endhint %}

## Agenda

## Brief Updates

[00:02](https://youtu.be/vXErKcmM-iE?t=2)

{% hint style="info" %}
Brief Updates/Notices from each participant - All
{% endhint %}

Stephen Whitenstall - 00:02

Steph Macurdy - 00:53

Kenric Nelson - 01:08

## Research Budget <a href="#docs-internal-guid-1cbf57a2-7fff-27b5-ef9b-9e017b4e1302" id="docs-internal-guid-1cbf57a2-7fff-27b5-ef9b-9e017b4e1302"></a>

#### Kenric Nelson <a href="#docs-internal-guid-1cbf57a2-7fff-27b5-ef9b-9e017b4e1302" id="docs-internal-guid-1cbf57a2-7fff-27b5-ef9b-9e017b4e1302"></a>

{% hint style="info" %}
Any Budget updates or issues ?
{% endhint %}

No updates this meeting

## Research Project Planning <a href="#docs-internal-guid-097619fc-7fff-df05-dc0c-dc8e89dc646e" id="docs-internal-guid-097619fc-7fff-df05-dc0c-dc8e89dc646e"></a>

#### Kenric Nelson / Stephen Whitenstall <a href="#docs-internal-guid-097619fc-7fff-df05-dc0c-dc8e89dc646e" id="docs-internal-guid-097619fc-7fff-df05-dc0c-dc8e89dc646e"></a>

02:02

{% hint style="info" %}
Any updates on Project Plan timetable and deliverables
{% endhint %}

#### Brief Update - Kenric

02:17

Let's see how the \[White Paper] drafts come together this month.

We'll have an After Town Hall to introduce what we're working on to the community and recruit reviewers.

Depending on our pace over the next month this may take a little bit longer than what we originally planned.

### The role of Delegated Representation in Blockchain Governance <a href="#docs-internal-guid-9f80fe74-7fff-67a0-e68e-ff9a3a64c4a9" id="docs-internal-guid-9f80fe74-7fff-67a0-e68e-ff9a3a64c4a9"></a>

#### Philip Lazos

#### Update from Kenric Nelson

03:38

\[Philip] did reach out to us and said that he will be adding his draft very soon.

### Forming consensus in governance documentation <a href="#docs-internal-guid-ca918fbf-7fff-af6c-da82-224d107f84fd" id="docs-internal-guid-ca918fbf-7fff-af6c-da82-224d107f84fd"></a>

#### Aharon Porath

#### Update from Kenric Nelson

04:09

I haven't read through it carefully, but he does have a significant amount that he's contributed. So I do see good progress there. And I plan to get together with him separately to go over that in more detail.

### Measuring Voting Power in a Delegated Representative Process <a href="#docs-internal-guid-f59c4f95-7fff-075a-8c98-a1f19b086bfb" id="docs-internal-guid-f59c4f95-7fff-075a-8c98-a1f19b086bfb"></a>

#### Steph Macurdy

[04:44](https://youtu.be/Q7UMeoJ-EVs?t=284)

I added to the section in the white paper, the general flow begins with what Kenric highlights as a good first example : the separation of powers between Cardano Foundation, Emurgo and IOG.

And how that simple example explains the bigger idea of Banzhof Power Indices.

I would like to provide the example from \[Wolfram] software as opposed to website that we currently have. But that's a good placeholder.

06:11

The second part addresses how when we relate this to Project Catalyst there's much more nuance and complexity.

And so when we want to think about how to actually do that calculation, what are the things we need to take into account and some of these things are limitations, some of these things are?

* What's the best way to represent information that we don't have ?
* What are some of the best ways to simplify \[the data set] so that it makes sense and can be handled computationally ?
* How technical do we want to be with reference to the Banzhof definition ?
* How much from the research papers do we want to cite in respect of the Banzhof definition ?
* Visualisations are the best way to articulate a big idea. Is that something that we want to see in this section here ?

#### Kenric Nelson

08:17

These are great questions. Because once you get started with formal definitions that can be pretty lengthy in itself.&#x20;

Whether we want to include that as part of the white paper depends on your time and on how it balances with the other sections.&#x20;

For this white paper it may be okay to just reference.&#x20;

#### Stephen Whitenstall

[09:11](https://youtu.be/Q7UMeoJ-EVs?t=551)

There's kind of a minimum isn't there? We need an absolute reference of what the Banzhof Power Index is. A need to refer to the definitive paper or the definitive reference

a? And then anything more than that will be some kind of exposition of that formal formal definition. We just thought, well, you're saying stuff.

### Differences in computation of Index

#### Kenric Nelson

[11:26](https://youtu.be/Q7UMeoJ-EVs?t=686)

I am concerned that we have not resolved the clear difference between the computation on the website I was using and the computation that your colleague had done. Did you get any clarification as to what the difference is ?

#### Steph Macurdy

12:05

I got clarification that there is difference. I did not get clarification why the definition from the research paper differs.

So I've not been able to identify what from the research paper is different from what's been implemented as the function.&#x20;

It's the question is kind of is that the right definition? Or is there some mistake in the research paper?

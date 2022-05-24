---
description: Meeting 2 of DAO Governance Literature Review - 10th May 2022
---

# Meeting 2

{% embed url="https://youtu.be/MZEqGvLw7Zg" %}

### Attendees

|                     |                         |
| ------------------- | ----------------------- |
| Amar Khan           |                         |
| Kenric Nelson       | Photrek                 |
| Philip Lazos        | IOG                     |
| Stephen Whitenstall | QADAO                   |
| Steph Macurdy       | Wolfram Blockchain Labs |

### Information

#### Community Governance Group

[https://quality-assurance-dao.gitbook.io/community-governance-oversight/](https://quality-assurance-dao.gitbook.io/community-governance-oversight/)

#### Meeting GitHub Task

https://github.com/Catalyst-Auditing/Community-Governance-Oversight-Coordination/issues/71

### Overview

After preliminary Zotero housekeeping, discussion moved onto Liquid Democracy papers.

### Context

[17:39](https://www.youtube.com/watch?v=MZEqGvLw7Zg\&t=1059s)

For context the papers we're looking at is background for D reps. Papers that are relevant to liquid democracy and in the context of IOGs implementation of D reps. - **Stephen**

Particularly methodologies for measuring power in these kinds of voting systems. - **Kenric**

[18:57](https://www.youtube.com/watch?v=MZEqGvLw7Zg\&t=1137s)

I'm not necessarily looking for this literature review to provide answers. But rather to help provide some guidance to the community about what the important questions are on these issues. And in defining good questions, I'm hoping to kind of motivate research and development within the community to try to tackle some of these questions. - **Kenric**

And the other contextual point is that this is part of an effort by Governance Oversight to do surveys within the community. A survey of the literature as a way to inform a more in depth conversation with the community and with IOG, with regard to the designs, and expectations we should have about the outcomes of the direct process. - **Kenric**

[20:40](https://www.youtube.com/watch?v=MZEqGvLw7Zg\&t=1240s)

Community Governance Oversight is a proposal that was submitted to Project Catalyst. It was jointly prepared with the community, IOG, Dor and Harris to oversee governance processes. It was funded in Fund 7, it may be funded in Fund 8. Part of that is to oversee D reps, Catalyst Circle Problem Sensing and Challenge Setting. - **Stephen**

### Review of "Power in Liquid Democracy"

[Link to paper](https://www.aaai.org/AAAI21Papers/AAAI-7700.ZhangY.pdf)

{% embed url="https://www.aaai.org/AAAI21Papers/AAAI-7700.ZhangY.pdf" %}

[24:50](https://www.youtube.com/watch?v=MZEqGvLw7Zg\&t=1490s)

What I'd like to do is use the tags to put our names so that we have a record of who provided the entry. So on your note, if you can add a tag with your name, that will be helpful. - **Kenric**

### Brief Summary

[26:11](https://www.youtube.com/watch?v=MZEqGvLw7Zg\&t=1571s)

The paper develops a theory of power for delegable proxy voting systems.

It defines a power index to measure the influence of voters and delegators.

A formal theory of power with a delegated proxy was lacking.

So the aim was to provide a theory to gain insight into how power may have been to be distributed among agents.

The authors analytically study the existence of pure strategy Nash equilibrium.

What does Nash equilibrium mean? Nash equilibrium is the most common way to define the solution of a non cooperative game involving two or more players. Each player is assumed to know the equilibria rooms, strategies of other players, and no one has anything to gain by changing only one's own strategy.

I think that might be helpful for just explaining what's the the importance of Nash equilibrium? - **Steph**

{% hint style="info" %}
See also [Steph's Notes](https://quality-assurance-dao.gitbook.io/community-governance-oversight/governance-processes/delegated-voting-drep/dao-governance-literature-review#stephs-notes-on-power-in-liquid-democracy) below
{% endhint %}

### Portfolio allocation of voting power

[28:06](https://www.youtube.com/watch?v=MZEqGvLw7Zg\&t=1686s)

One of my immediate first thoughts was if people are delegating votes are we going to have a portfolio? Are we going to get to a point similar to how you allocate your financial portfolio? Are you going to do a portfolio allocation of voting power?

If I have 100 votes am I going to be able to choose a little bit here or allocate a little bit there ? - **Steph**

28:41

From what IOG has communicated that is the intent. They haven't rolled it out yet. But part of the idea behind liquid democracy and the plans for the delegated reps is that you wouldn't necessarily delegate all your power to one representative, but you might spread that power across several representatives. - **Kenric**

### **Researching dRep's background**

[29:11](https://www.youtube.com/watch?v=MZEqGvLw7Zg\&t=1751s)

I envision a research report that says this delegate rep is experienced in a particular area. There is evidence of what they understand and their previous voting record.

This is their Wallet account. This is what they currently hold. This is how long they've been participating.

And instead of me knowing about those things intimately it is enough that I just I need to know the reputation of somebody.

And if I feel strongly about it, then I'm 50% allocated to them. And if I just want to make sure I hedge myself, I'm 10% to the opposite extreme.

In the paper, they reference something called Liquid feedback. A website called liquid feed. - **Steph**

{% hint style="info" %}
**Liquid Feedback -** https://liquidfeedback.com/en/
{% endhint %}

### Liquid Feedback

[30:45](https://www.youtube.com/watch?v=MZEqGvLw7Zg\&t=1845s)

Liquid feedback brought up the idea of favoring preferences and giving somebody the option of having a secondary choice. And where, as opposed to only having all all on one vote, it's, you do have the ability to represent secondary, and third choices. - **Steph**

### Transitive delegations

[31:15](https://www.youtube.com/watch?v=MZEqGvLw7Zg\&t=1875s)

One main starting point of our paper is a controversial feature of liquid democracy. That is, transitive delegations may, in principle, lead to disproportionate accrual of power, thereby harming the democratic legitimacy of the resulting vote.

Kenric, this is a thing that you focus on a lot. - **Steph**

### Banzhaf power index <a href="#firstheading" id="firstheading"></a>

[31:33](https://www.youtube.com/watch?v=MZEqGvLw7Zg\&t=1893s)

The Banzhaf power index is a power index, defined by the probability of changing an outcome of a vote where voting rights are not necessarily equally divided among the vote, voters or shareholders. - **Steph**

### References

### Steph's Notes on "Power in Liquid Democracy"

**Steph Macurdy: The paper develops a theory of power for delegable proxy voting systems.** We define a power index able to measure the influence of both voters and delegators.

However, a formal theory of power in voting systems with delegable proxy is lacking. We aim at providing such a theory here, and use it to gain insights into how power may happen to be distributed among agents involved in decision-making with liquid democracy

We analytically study the existence of **pure strategy Nash equilibria in such a model**. Finally, by means of simulations, we study the effect of relevant parameters on the emergence of power inequalities in the model.

Nash equilibrium is the most common way to define the [solution](https://en.wikipedia.org/wiki/Solution\_concept) of a [non-cooperative game](https://en.wikipedia.org/wiki/Non-cooperative\_game) involving two or more players. In a Nash equilibrium, each player is assumed to know the equilibrium strategies of the other players, and no one has anything to gain by changing only one's own strategy. (Wikipedia)

Delegable voting gives rise to so-called "transitive delegations."

Can either cast vote directly or delegate, passing votes one has accrued further to another proxy.

1. Portfolio allocation of votes
2. Snapshot results of different governance implementations

Liquid Feedback - https://liquidfeedback.com/en/

Favoring preferences and secondary choice.

"The starting point of our paper is a controversial feature of liquid democracy: transitive delegations may in principle lead to disproportionate accrual of power, thereby harming the democratic legitimacy of the resulting vote."

"is a [power](https://en.wikipedia.org/wiki/Power\_\(social\_and\_political\)) index defined by the [probability](https://en.wikipedia.org/wiki/Probability) of changing an [outcome](https://en.wikipedia.org/wiki/Outcome\_\(game\_theory\)) of a [vote](https://en.wikipedia.org/wiki/Voting) where voting rights are not necessarily equally divided among the voters or [shareholders](https://en.wikipedia.org/wiki/Shareholder)." - (https://en.wikipedia.org/wiki/Banzhaf\_power\_index)

"Winner take all dynamics when its only one vote per person?"

### Banzhaf Power Index

{% embed url="https://en.wikipedia.org/wiki/Banzhaf_power_index" %}

[Banzhaf Power Index - Wolfram Demonstrations Projec](https://demonstrations.wolfram.com/BanzhafPowerIndex/)t

> The Banzhaf index is a measure of how probable it is that someone's vote will change the outcome of an election in settings in which voters may have unequal numbers of votes. This Demonstration examines a scenario with six voters, each of whom have a user selectable number of votes. You can also determine the percentage of total votes needed to win. From this data, the Demonstration shows all the winning coalitions that can form and all the members of each coalition ("the swing voters") who, if they had voted differently, would have changed the outcome of the election. The Banzhaf index, which ranges from 0 to 1, is the percentage of times each voter is a swing voter over all possible winning coalitions.

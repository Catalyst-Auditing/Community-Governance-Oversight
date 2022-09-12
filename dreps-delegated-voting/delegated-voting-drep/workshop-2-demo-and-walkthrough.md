---
description: Demo and walkthrough of how dRep registration and voting/delegating works
---

# Workshop 2 - dRep Demo and walkthrough

## Slides

[Link to slides](https://docs.google.com/presentation/d/1ZMTSlV17ScfCuDqBgHleKWmhtYn9VIiwQdm7OjUbvCo/edit?usp=sharing)

{% embed url="https://docs.google.com/presentation/d/1ZMTSlV17ScfCuDqBgHleKWmhtYn9VIiwQdm7OjUbvCo/edit?usp=sharing" %}

{% hint style="info" %}
**Note**: Session B (the second session) was the more definitive of the two sessions delivered, and so is shown first.
{% endhint %}

## Session B <a href="#session-a" id="session-a"></a>

Thursday 8th September 2022, 17:00 UTC

### Video

{% embed url="https://youtu.be/b7nXUBXCZoA" %}

### Presentation part 1: registering as a dRep

**0:18** Welcome\
**3:08** Introduction (Jack Briggs, IOG)\
**5:32** Agenda; and how this session will be documented

**6:16** Recap – what was covered in workshop 1\
**8:32** Recap – what is liquid democracy?\
**9:15** Recap – why delegation and dReps?

**11:07** dRep registration\
&#x20;\- 11:34 Main homepage of the GVC (Governance Voting Center) dApp \
&#x20;\- 11:56 No more need for QR codes and PINs when voting\
&#x20;\- 13:07 Design is finalised, but some content still to be added\
&#x20;\- 13:25 dRep registration form – basic info\
&#x20;\- 14:03 Your dRep profile\
&#x20;\- 14:39 Tags for your interests, which will be aligned with IdeaScale tags\
&#x20;\- 14:59: Feedback is welcome – but not clear where feedback should be given\
&#x20;\- 15:09 Your socials links\
&#x20;\- 15:31 Privacy, Terms and Conditions, KYC and Proof of Life

### Questions from Chat

**16:14 Eystein Magnus Hansen: What happens if the delegation vote and the user votes differ? Can the user’s vote override the delegation vote?**\
__**Answer:** In the first iteration, it will definitely not be possible to override the dRep’s’ vote on an individual proposal that you care about. For future iterations, maybe - we need to understand why people would want to do that.

**17:42 Tomi Astikainen: Can a dRep delegate their own voting power to another dRep?**\
**Answer:** No; that breaks the purpose of dReps. \[<mark style="color:red;">Note: but see below - this is possible if you create a separate wallet.</mark>]

**18:07 Zoé Selina: Do voters have to choose between delegating, and voting directly; or can they delegate a percentage of their voting power?**\
**Answer:** You cannot partially delegate. Either you delegate 100% of your voting power, or you vote yourself. Partial delegation might be possible in future, but not for this first iteration. The workaround is to have 2 wallets; one delegated, and the other for voting directly.

**19:49 Zoé Selina: Can a dRep delegate their own voting power to another dRep?**\
**Answer:** Yes, if you have two wallets. You would still need to have at least 500ADA in each wallet

**20:45 Tomi Astikainen: Can you delegate e.g. 50% to one dRep, 30% to another and 20% to a third?**\
**Answer:** Yes – this will be covered later in the slides.

**21:20 Tommy Frey: Will a downvote count as a vote?**\
**Answer:** Yes.

**21:33 Zoé Selina: There are many voices against downvoting. Why was this adopted to dReps without having the conversation?**\
**Answer:**  it is currently following the original treasury paper implementation,  [https://eprint.iacr.org/2018/435.pdf](https://eprint.iacr.org/2018/435.pdf) with the 3-way “yes”, “no” and “abstain”. This doesn’t mean it can’t change in the future.

**22:10 Eystein Magnus Hansen: Which wallets are supported?** \
**Answer:** We are actively working with all the community wallets that have expressed interest: Eternl, Typhon, Yoroi, Flint, Lace. It will depend which ones decide to implement it. Catalyst is being built as wallet-agnostic.

**23:40 Sebastian Pereira: If a dRep fails to vote for the minimum amount of proposals, do delegators still receive rewards?**\
**Answer:** Yes. The dRep will not, but their delegators will; and their voting power will be counted.

**24:05 Voltaire Valdellon: This delegation is Catalyst-specific, and separate from Ouroboros?** \
**Answer:** Yes, this is Catalyst-specific.

**24:21 Nori Nishigaya: Will there be support for SPOs and using the command line for delegating their voting power?**\
**Answer:** There is some tooling required on this, so it may not be possible for the MVP; but we are working with Martin from ATADA on it, who already manages many current SPO scripts, and the CLI voting tools. \[<mark style="color:red;">**Note:**</mark> <mark style="color:red;"></mark><mark style="color:red;">for further info, see Martin's GitHub repo</mark> [https://github.com/gitmachtl](https://github.com/gitmachtl)]

**25:29 several commenters: Will there be an opportunity to set custom tags in your dRep profile?**\
**Answer:** Not at launch, but maybe in the future.\
**26:21 Kyle** I recommend using 2 different sets of tags – primary roles, maybe aligned with proposal categories; and ancillary/secondary skills.\
**Answer:** This is the first iteration – we will certainly want to improve.

### Presentation part 2: dRep dashboard and Voting Center

**28:12** dRep dashboard\
**28:53** Voting centre\
&#x20;\- 29:05 Landing page\
&#x20;\- 29:19 List of dReps  – order is randomised: there is no hierarchy. Oversaturated dReps are filtered out.

### **Clarification on how saturation and reward are calculated:**

**31:16** The voting-power cap is 1% of the total _**voting**_ stake – i.e. the total amount of ADA used to vote in a particular fund. But dRep rewards are capped at 1% of the total _**delegated**_ stake. These are two different numbers. \
**For example**<mark style="color:red;">,</mark> if there is 1 billion ADA total voting stake (i.e. the total amount of ADA used in a fund), but only 100 million of that was delegated, then the maximum voting power that a dRep can have is 10 million ADA (1% of the 1 billion total), but a dRep only needs to have 1 million ADA to earn their full rewards, because it's 1% of the delegated total, 100 million, rather than 1% of a billion.\
**33:23** All these parameters will eventually be able to be changed by the community.

### **More questions from Chat**

**33:48 Henry Wang: What's the timeline for approving the applications \[**_**to be a dRep**_**]?**\
**Answer:** We're targeting voting for Fund 10, so there will have to be an earlier onboarding, to allow time for dReps to be listed and get delegation ahead of the vote for Fund 10.&#x20;

**34:34 Alejandro Gelves Gelves: Are voting rewards for individuals the same, whether they delegate or vote individually?**\
**Answer:** The rewards will be the same; but your voting power will have greater influence if you delegate. Your voice is heard louder if you delegate.

**35:03 Tommy Frey: What does the tag “Defi” cover? Does it indicate NFTs, cNFTS, etc?**\
**Answer:** IOG will elaborate on the definitions of the categories and tags.

**35:40 Gustavo Pugliese: Are dRep votes public?**\
**Answer:** Yes; they are public by design. When you sign up as a dRep, and accpt the privacy policy, you accept that your voting from that wallet will be public during the time that you are a dRep. There is also off-chain transparency: you must publicly provide written rationales for the way you voted. These are available to everyone, not just to those who delegate with you. So there are 2 parts to the transparency – on-chain and off-chain.\
**36:59** There are two different voting plans: one for dReps, and another for direct voters. Once the vote is complete, the dRep voting plan is made public, and the dRep votes become a matter of public record.

**37:27 several commenters: As a dRep, how do I account for my own wallet's voting power?**\
**Answer:** See slide #17 - the breakdown between staked and delegated ADA is displayed in your profile.

**38:17 Jason Toevs: Are the wallet integration requirements open source?**\
**Answer:** Yes. It will be a CIP – I believe it is [CIP 62](https://github.com/cardano-foundation/CIPs/pull/296).  We are working with the wallets to come up with the CIP. It will be publicly available, and anyone can build a similar experience, as long as they follow the same principles.

**38:58  Alejandro Gelves Gelves: Is it possible to have whale dReps, that get maximum reward even though no one delegates to them?**\
**Answer:** Yes. If you are a whale, you could create 2 wallets, register one as a dRep, and delegate to yourself. But depending how big a whale you are, you might therefore lose some of your voting influence, because as a dRep your voting influence is capped at 1%. And you would still have to meet the minimum dRep requirement of voting on 60 proposals and 20 Challenge proposals; so we would be paying a whale to work, which is not a bad thing.

**40:20 Juana Attieh: In that situation, how will your own voting power be separated from the ones accumulated by your delegators?** \
**Answer:** There’s no distinction. Your voting power is your voting power, and that's that.

**40:56 Zoé Selina: On making the vote public – are there 2 stages of voting, one for dReps and one for direct voters?**\
**Answer:** No, it is all simultaneous. While people are voting, everything is private, and nobody knows what the progress of the vote is. But after the vote, how dReps voted will be unlocked, so delegators can verify what choices their dRep made.

**42:33 Sebastian Pereira: In the case of failure by the dRep (for example, if the dRep fails to vote for enough proposals), how will the rewards for their delegators be calculated?**\
**Answer:** The dRep will not be rewarded; but the voting power will still count, and the voters will still be rewarded, so the dRep is the only one that's penalised.

**43:06 Eystein Magnus Hansen: Are there plans to track wallet voting history with the status of “yes”-voted projects; e.g did project succeed, etc?**\
**Answer**: Yes. Voting history is one of our future plans, and we hope to demo it in a future workshop like this. Obviously, it will be an opt-in; you will be able to choose whether you want your voting history to be available to you.&#x20;

**43:54 Tomi Astikainen: Voter rewards are always tied to the voting power snapshot taken. Therefore it should not matter whether you "keep all eggs in one dRep basket" or split it among many - at the end of the day, your voting rewards are still the same, right?**\
**Answer:** Yes.

**44:22 Jason Toevs: What order is the list of dReps displayed in?**\
**Answer:** As mentioned earlier, it’s randomised. Oversaturated dReps are not shown initially \[<mark style="color:red;">**NOTE**</mark>: as mentioned later, you can change your filters to display them].

**44:47 Sef: How many dReps are needed? How many hours a day/week it could take to accomplish the job?**\
**Answer:** It will depend on whether you already have an audience that trust you and will delegate immediately to you. Some dReps will need to advertise a bit more; similar to stakepools. \
That’s the work to secure delegation. The other work is writing a public rationale for your vote on at least 60 proposals and 20 challenges; which should take you 5 minutes each. Then there is the time it takes to actually vote, which will depend on how much you read the proposals and how much research you do. So we imagine intensive work for a month in each Fund. But it will be different for everybody.&#x20;

**46:28 Sebastian: How far are the rewards of delegators tied to the performance of the dRep? e.g. if a dRep votes for more than the minimum 60 proposals, will that increase the reward of their delegators? Will it create competition between the dReps on who can vote the most?**\
**Answer:** We haven't looked at scaling rewards based on performance; we have only set minimum requirements. But the idea is open to debate, and the community can decide to change the parameters in future.

### Presentation part 3: How to delegate

**48:09** Slide 21: On the right you can see “voting delegation”, which tells you your current state of delegation as an end user.\
**48:42** Slide 22: what a dRep’s profile looks like to a voter, and how a voter can add a dRep to their delegation card.\
**49:34** How a voter can manage the voting power they allocate to each dRep that they choose to delegate to.\
**50:06** Summary \
&#x20;\- 50:18 IOG are still working on how the Proof of Life review will work.\
&#x20;\- 50:56 Delegation values reset after each fund – this is as a safeguard to avoid concentration of power, but it’s a parameter that the community could decide to change.

### More questions from Chat

**52:32 Darlington Wleh: Will the open APIs be published on the same timeline as this UI?**\
Answer: Yes, the plan is to release them together, aligned with Fund 10.

**53:20 Eystein Magnus Hansen: Is a dRep’s voting power shown to the delegators?**\
**Answer:** Yes. Obviously, it depends on timing: it will change as we get closer to the snapshot moment where the total delegated amount is confirmed.

**54:21 Kenric Nelson: If a dRep's delegation goes over 1%, can people still delegate to them?**\
**Answer:** We will not stop them, but we will give a warning that they are delegating to someone who's already oversaturated and they will lose their voting rewards as a result. If you still want to delegate, we can't stop you, and we shouldn't stop you.\
**Kenric Nelson:** Part of why its important to allow people to delegate to oversaturated pools, is to protect against the following type of scenario: A whale saturates a dRep and then at the last minute removes all of their delegation, leaving the dRep without delegation.

**55:10 Voltaire Valdellon: It was mentioned previously that the dReps in the top 150 of voting power would receive rewards.  Is this in addition to or separate from the Direct Voting requirements?**\
**Answer:** It’s separate – direct voting is different from delegated voting, and they are separate.

**55:43 Zoé Selina: Why are oversaturated reps not shown? Oversaturated stake pools are always shown, and it's your personal decision whether you want to go into it or not.**\
**Answer:** It’s only initially that they do not display; if you change your filter, they will show. So we are not trying to hide the information; we are just making it harder for users to waste their voting rewards.\
A dRep cannot have more than 1% voting power; it’s a safeguard to prevent power concentration. Delegating to a dRep who has reached that limit would be a wasted vote, both for rewards and for your vote – you might as well vote directly or delegate to someone else.

**57:54 Joanna:  Can every wallet choose to delegate their entire voting power to 10 different dReps? Or do they have to allocate their voting power \***_**across\***_** 10 different dReps?**\
**Answer:** You cannot partially delegate your voting power. So when you delegate, you delegate all your voting power; and you can delegate it to up to 10 dReps.\
**58:27 Joanna:** But then, if two different dReps voted on the same proposal, that's doubling my voting power, whereas now I can only vote once on one proposal?\
**Answer:** You have a weight attached to your voting power – see the percentage sliders shown on slide #24. The slider will move dynamically; you might want to give 90% to one dRep, and 10% to another. It's your prerogative.

**59:22 Alejandro Gelves Gelves: Once a dRep is saturated, what prevents more people delegating to them?**\
**Answer:** To reiterate – nothing. But they will see a warning that they are about to waste their voting power.

**59:47 Rodolfo Miranda: Are the past votes of a dRep’s wallet public or private?**\
**Answer:** For votes from before you became a dRep: one requirement to become a dRep is that you need to have voted in a previous fund. To maintain privacy e.g. on how much ADA you personally hold, you can create a new wallet as a dRep; and we would validate that you voted in a previous fund via the proof of life review, a private meeting which we still need to define. For votes in future Funds, we want to let users see a dRep’s previous voting history, so we are planning that for a future iteration.\
**In chat from Harris Warren, IOG:** As long as you are a registered dRep your votes will be public.  If you delete your dRep profile then your votes will be private by default.

**1:02:07 Tomi Astikainen: **_****_** Can **_****_** whales have multiple wallets and get rewarded multiple times?**\
**Answer:** For voter rewards, it will be the same as if they voted from one wallet with all their ADA in it, because that's how voter rewards are calculated. If they were to try to become more than one dRep, they would be filtered out at the Proof of Life stage.

**1:02:52 Eystein Magnus Hansen: Will it be frowned upon for dReps to make public how they plan to vote?**\
**Answer:** It’s a matter of transparency. A dRep says in their profile what types of projects they will vote for, and people will delegate to them based on that. If they then vote for something different, that could cause problems with people who delegated to them. But their written rationales should explain why they voted as they did. People need to know they can trust you as a dRep to use _their_ voting power the way you said you would.

**1:04:22 Jason Toevs: Are the delegated wallet addresses made public along with the dRep votes after the Tally?**\
**Answer** If you're voting directly, your vote is kept private. If you've delegated, your wallet is not casting the vote; the dRep is doing it on your behalf, and their wallet is made public.

**1:04:47 Alejandro Gelves Gelves: Is there a plan to be more transparent in the voting results? A dashboard that shows all projects and their upvotes and downvotes. and maybe also the wallets? How do we know that our votes, and dRep votes, were actually counted? Shouldn’t this be automated and perhaps real-time?**\
**Answer:** Yes. We need to provide better tooling to build more transparency into future versions. The past history of the votes that have been cast will all become available.  Our goal is to give you the tools to verify the results yourself.&#x20;

**1:06:33 Tomi Astikainen: Can a voter whale register ten wallet addresses, vote for (and saturate) ten different dReps and get 10 x rewards?**\
**Answer:** No, because voter rewards are based on the total ADA you have. So whether you  vote with all of your ADA in one wallet or split it in 10, the actual amount doesn’t change.\
**Later answer 1:09:01:** The whale would have a reduction in voting rewards if they oversaturate a dRep. So let's say one whale has 2% voting power, and they delegate it all to one dRep - they slash their voting rewards in half. So they could decide to have two wallets, do 1% to one dRep, and 1% to another, and get their full reward. But they could equally get their full reward if they just voted directly without using a dRep. So there isn't any actual increase in monetary gain.

**1:07:38 Christophe Garant: Will voting tools make it easier to 1) vote/delegate with multiple wallets, 2) create a voting list easier, select multiple proposals, sortable, smart query?**\
**Answer:** Yes, we hope to build all these functionalities, though not for Fund 10. We plan for batch voting, advanced filters and more. But we want to be realistic and make sure we have a usable experience ready for Fund 10. Once it's out there, we will iterate with the community.

**1:09:39 Tommy Frey: Keeping in mind the minimum numbers of PA and VPA reviews desired - what number of dRep votes per proposal is desired?** \
**Answer:** That's not a parameter that we've discussed. For the first iteration, a good success metric could be simply that 20% of all voting stake was delegated. But we can’t predict how people will behave; and we want the community to also define some of these metrics.

**1:11:11 Tommy Frey: And what is the total dRep budget?** \
**Answer:** The dRep rewards come out of the voter reward pot. A percentage of each fund goes to those rewards, and the dReps will be coming out of that percentage. The total amount an individual dRep can earn will be $3,060. I can't remember why we settled on that amount – I think there’s a percentage max to go with the total fund pot, versus the percentage of how much is available to voter rewards. But rewards can be discussed and changed in future.\
**1:12:21 Tommy Frey:** I was trying to find out the number of dReps that you want. Rewards are only a part of the budget – there is also the cost of developing a  software program, the API, doing these workshops. Why is Cardano Foundation so interested in liquid democracy that you're putting in how much money into it? As a business person, as an investor - what's the total budget earmarked for this project?\
**Answer:** I don’t have the figures to hand. The reason for it is the broader plan that we have for governance for Cardano – we believe delegation is important, and we hope the experiment will show we are correct.

**1:14:08 Alejandro Gelves Gelves: Is it possible to have “dead” voting power - dReps that do not review, and voters who delegated to them but do not switch, since they still get rewarded?**\
**Answer:** As a direct voter you only need to cast one vote to get your full voting reward. \[<mark style="color:red;">**Note:**</mark> <mark style="color:red;"></mark><mark style="color:red;">misspeaking? In F10 there are minimum requirements for direct voters to get rewards - they must vote on at least 30 proposals and 10 challenge proposals. See next question.]</mark> But with a dRep, if they don't cast any vote, do the delegates get the reward? I'm not sure they do.  I think it's just a mechanical rather than a  philosophical rule. But we need to check.\
<mark style="color:red;">**ACTION ITEM:**</mark> Danny and Jack to take this question back to confirm.

**1:15:05 What is the minimum requirement for the direct voters in order to be eligible for the voting rewards?**\
**Answer:** In Fund 10, it’s 30 proposals, and 10 Challenge proposals. If you vote on fewer, your voting power will still count; you just won't get any voter rewards. If you delegate to one dRep, you get your full voting reward. So we would encourage voters who are short of time to delegate their voting power.&#x20;

**1:16:22 Christophe Garant: Will dRep wallets be kept private?**\
**Answer:** No, they are public, and we show them in the dRep’s profiles.

**1:16:37 Tommy Frey: Can SSI be used as an experiment for this?**\
**Answer:** Yes; we are considering it – but not for F10. There's also a concurrent effort under way to pilot SSI with VPAs.

**1:17:29 Kyle Wood: Will there be any restriction on dReps voting on their own proposals?**\
**Answer:** This was discussed in the first workshop in June \[see [**here**](https://quality-assurance-dao.gitbook.io/community-governance-oversight/dreps-delegated-voting/delegated-voting-drep/workshop-1)]. Originally, we had said no; and then someone came up with a good example of why you should be allowed to. We spoke to the research team at IOG and realised it made sense; so yes, you can vote on your own proposals. But you should declare your intentions openly in your profile, so people that delegate to you know your intention.

**1:18:57 Can every wallet delegate to 10 different dReps?**\
**Answer:** Yes. If you have a wallet, it doesn't matter what the wallet provider is - anyone can delegate, as long as the wallet supports the new CIP 62 feature which will be coming out with Fund 10. <mark style="color:red;">\[</mark><mark style="color:red;">**NOTE:**</mark> <mark style="color:red;"></mark><mark style="color:red;">This answer may not address the question that was asked]</mark>

**1:19:50 Alejandro Gelves Gelves Is there a queue that is recorded when you delegate to a dRep, which remembers who delegated first and last? If I delegate when saturated and then some people leave, would I be first in line to be included in rewards?**\
**Answer:** It all works at snapshot. Whatever was in the past or may happen in the future does not apply. We will be able to show you a continuous snapshot of what your current voting power is. There still might be a 24 hour delay; but ultimately, the calculations happen at snapshot. <mark style="color:red;">\[</mark><mark style="color:red;">**NOTE:**</mark> <mark style="color:red;"></mark><mark style="color:red;">This answer may not address the question that was asked]</mark>

**1:21:23 Tomi Astikainen: What are the implications if I am a whale, and I create 100 different wallets and hire 100 people to do the dRepping for me; they do the PoL but essentially it's one big team against the world?**\
**Answer:** The “frontman” dRep would have to identify themselves during Proof of Life and have control of that wallet; so they would have to have control of that proportion of a whale's wallet. So that whale would therefore have to trust that frontman, which is probably unlikely. But we should always look at edge cases as those are where attacks happen. \
<mark style="color:red;">**ACTION ITEM:**</mark> Question noted: to be discussed further.

**1:23:06 Andreas Sosilo: Are we no longer using the Catalyst voting app in Fund 10?**\
**Answer:** Our goal for Fund 10 is for dReps  to be able to use it to vote and to manage their profiles; and for delegators to use it to find dReps and delegate to them. The third element is the active voter – for them, the Catalyst voting app, and QR and PIN codes, will remain the primary voting method in F10, unless they are brave enough to risk a beta app. We don't want to stop anyone artificially from using the app; but we are not recommending general public use for F10. So the main focus of the Voting Centre for F10 is for dReps, and we hope it will be a real alternative for everyone in F11.

**1:25:31 Eystein Magnus Hansen: Is there a protection mechanism in place against blocking voting registration on the API; DDoS (distributed denial-of-service) attack and such?**\
**Answer:** Yes. All APIs that we build, regardless of purpose and use, go through standard API best practices, which includes protecting against DDoS. That's extremely standard. API's are much more stable technology than even blockchain; so I think we have much more well-defined security best practices there.

**1:26:40 Voltaire Valdellon: If wallets are static and public, is there a workaround if a wallet gets compromised in some way?**\
**Answer:** Any dApp could have this problem. The first thing you should do is to disconnect your wallet, to revoke your permissions as a user from the dApp. Beyond that, if there is something urgent, you can reach us via Discord and Twitter. But it's always a best practice to stay aware of dApps you're authorised in your wallet; and if you're sure you are not using that dApp ever again, disconnect your wallet. There's no need to give permission indefinitely to a dApp.

### Close

**1:28:38** Wrap-up and closing remarks\
Recording ends: **1:30:26**

### **Full Chat text**

{% file src="../../.gitbook/assets/Chat, session B dRep workshop, 8th Sept 2002.doc" %}

## Session A

Thursday 8th September 09:00 UTC

### Video

See https://quality-assurance-dao.gitbook.io/community-governance-oversight/dreps-delegated-voting/delegated-voting-drep/workshop-2-demo-and-walkthrough for full summary and slides.

0:00 - Preamble&#x20;

### Presentation

{% hint style="info" %}
**Note :** Images of each Slide from the presentation are reproduced here for context
{% endhint %}

#### 04:17 - Slide Presentation - Jack Briggs&#x20;

<figure><img src="../../.gitbook/assets/Slides-01.png" alt=""><figcaption></figcaption></figure>

#### 05:17 - Welcome to another experiment&#x20;

<figure><img src="../../.gitbook/assets/Slide-02.png" alt=""><figcaption></figcaption></figure>

#### 05:49 - Things may break&#x20;

<figure><img src="../../.gitbook/assets/Slide-03.png" alt=""><figcaption></figcaption></figure>

#### 06:05 - Agenda&#x20;

<figure><img src="../../.gitbook/assets/Slide-04.png" alt=""><figcaption></figcaption></figure>

#### 06:38 - Recap&#x20;

<figure><img src="../../.gitbook/assets/Slide-05.png" alt=""><figcaption></figcaption></figure>

#### 08:34 - What is Liquid Democracy ?&#x20;

<figure><img src="../../.gitbook/assets/Slide-06.png" alt=""><figcaption></figcaption></figure>

#### 09:09 - Why Delegation and dReps ?&#x20;

<figure><img src="../../.gitbook/assets/Slide-07.png" alt=""><figcaption></figcaption></figure>

#### 10:36 - dRep Registration - Abhiroop Sharma&#x20;

<figure><img src="../../.gitbook/assets/Slides-08.png" alt=""><figcaption></figcaption></figure>

#### 11:27 - Voting Center&#x20;

<figure><img src="../../.gitbook/assets/Slides-09.png" alt=""><figcaption></figcaption></figure>

#### 12:21 - Vote as an expert&#x20;

<figure><img src="../../.gitbook/assets/Slides-10.png" alt=""><figcaption></figcaption></figure>

#### 12:52 - Basic Information&#x20;

<figure><img src="../../.gitbook/assets/Slides-11.png" alt=""><figcaption></figcaption></figure>

#### 13:47 - Profile&#x20;

<figure><img src="../../.gitbook/assets/Slides-12.png" alt=""><figcaption></figcaption></figure>

#### 14:19 - Expertise / Interests&#x20;

<figure><img src="../../.gitbook/assets/Slides-13.png" alt=""><figcaption></figcaption></figure>

#### 14:53 - Socials&#x20;

<figure><img src="../../.gitbook/assets/Slides-14.png" alt=""><figcaption></figcaption></figure>

#### 15:27 - Privacy&#x20;

<figure><img src="../../.gitbook/assets/Slides-15.png" alt=""><figcaption></figcaption></figure>

#### 15:50 - Submit Application

<figure><img src="../../.gitbook/assets/Slides-16.png" alt=""><figcaption></figcaption></figure>

### Questions

#### 16:34 - Question - What does it mean for a wallet address to remain fixed ?&#x20;

Answer -&#x20;

#### 17:21 - Question - Is the right to be forgotten universal ?&#x20;

Answer -&#x20;

#### 17:51 - Question - Will this be Open Source ? Can others create an alternative front end ?&#x20;

Answer -&#x20;

#### 18:31 - Question - Does the address become a public metric - so everyone will know how much ADA is in my wallet ?

Answer -&#x20;

#### 20:13 - GVC - Governance Voting Center acronym&#x20;

Answer -&#x20;

#### 20:51 - dRep Dashboard&#x20;

<figure><img src="../../.gitbook/assets/Slides-17.png" alt=""><figcaption></figcaption></figure>

#### 21:49 - The new voting center&#x20;

<figure><img src="../../.gitbook/assets/Slides-18.png" alt=""><figcaption></figcaption></figure>

#### 21:55 - Delegate your voting power to dReps&#x20;

<figure><img src="../../.gitbook/assets/Slides-19.png" alt=""><figcaption></figcaption></figure>

#### 22:28 - Experts helping to grow Cardano&#x20;

<figure><img src="../../.gitbook/assets/Slides-20.png" alt=""><figcaption></figcaption></figure>

#### 22:54 - List of dReps

<figure><img src="../../.gitbook/assets/Slides-21.png" alt=""><figcaption></figcaption></figure>

### Questions

#### 23:06 - Question - Will delegators to a dRep remain anonymous ?&#x20;

Answer -

#### 23:51 - Question - Elaborate on anonymous&#x20;

Answer -&#x20;

#### 23:54 - Question - As a dRep can I identify the wallets that are delegating to me ?&#x20;

Answer -

#### 24:09 - Question - Would the dRep be exposed to any regulatory issues around KYC (knowing your customer) regarding the wallets that are delegating.&#x20;

Answer -&#x20;

#### 25:26 - Question - As a dRep should I make a new QR code ?&#x20;

Answer -&#x20;

#### 26:28 - Question - If I use the same wallet that I have been using (for voting) I don't have to re-register ?&#x20;

Answer -&#x20;

#### 26:54 - Question - I thought this was going to be part of Lace ?&#x20;

Answer -&#x20;

#### 27:56 - Question - How easy will it be for a group to handle a dRep account ?&#x20;

Answer -&#x20;

#### 29:07 - Question - Is there a section in the GVC (Governance Voting Center) for users to skip the dRep delegation ?&#x20;

Answer -&#x20;

#### 30:07 - Question - I read somewhere that future dReps had to vote in Fund 8 in order to actually become dReps ?&#x20;

Answer -&#x20;

#### 31:12 - Question - At that point (after proof of life) you can still create a new wallet&#x20;

Answer -&#x20;

#### 31:21 - Question - So we would have to identify our wallets as part of that proof of life ?&#x20;

Answer -&#x20;

#### 31:55 - Question - Do we have any rating for each dRep after each Funding round ?&#x20;

Answer -&#x20;

#### 32:47 - Question - Currently Stakepool Operators (SPOs) have a special process to register themselves in the Catalyst Voting App using the CLI voting tools. Will a SPO be able to connect with their pledge so it counts towards voting ?&#x20;

Answer -&#x20;

#### 34:13 - Question - How public will Proof of Life data be and does it comply with all the Right to be Forgotten legislation ?

Answer -&#x20;

#### 36:26 - An individual dRep profile&#x20;

<figure><img src="../../.gitbook/assets/Slides-22.png" alt=""><figcaption></figcaption></figure>

#### 37:04 - Voting delegation&#x20;

<figure><img src="../../.gitbook/assets/Slides-23.png" alt=""><figcaption></figcaption></figure>

#### 37:34 - Add another dRep&#x20;

<figure><img src="../../.gitbook/assets/Slides-24.png" alt=""><figcaption></figcaption></figure>

#### 38:13 - Your voting power has been delegated&#x20;

<figure><img src="../../.gitbook/assets/Slides-25.png" alt=""><figcaption></figcaption></figure>

38:38 - Summary

41:37 - Question - What if a dRep votes at random without understanding what the proposal is about ?&#x20;

42:39 - Question - Is there any public testing ground for dReps ?&#x20;

43:51 - Question - Does the GVC (Voting Center) link the wallet address of every delegator to the profile they create on the GVC ? So if the delegator uses their real name does that mean they are doxxing their wallet address ?&#x20;

44:49 - Question - Could we have a private dRep, in the sense it isn't shown on the list ? For example I may want my family to delegate to me but I do not want others to do so. 46:11 - Question - But there is a Cap right ?&#x20;

47:46 - Delegation snapshot and limits&#x20;

50:24 - Question - Is a fee charged to delegators every time they set or change a dRep in the voting center ?&#x20;

51:50 - Question - Could you elaborate on what is the minimum amount of delegated ADA that a dRep needs to have to be active ?&#x20;

53:21 - Question - When is the total delegated stake number calculated ? At what point in the process ?&#x20;

53:37 - Question - Could you clarify the difference between staked ADA and delegated ADA ?&#x20;

54:42 - Question - What voting stake is determined at the time of this snapshot ?&#x20;

55:19 - Question - Timing - when is the total delegated vote stake calculated ?&#x20;

56:12 - Question - Saturation concept - Saturation is based on voting stake or delegated stake ?&#x20;

57:12 - Question - This effects more the voter delegating to you ?&#x20;

58:28 - Question - Lets say I am a dRep, I have a pretty average group of delegators and I am well below saturation.&#x20;

1:01:49 - Question - 1 Billion voting stake. As a dRep your stake is maxed at 1% what levels will you need ?&#x20;

1:04:18 - Question - So these levels would enforce a cap on the number of dReps ?&#x20;

1:06:38 - Question - The voting rationale is not the main aspect ?

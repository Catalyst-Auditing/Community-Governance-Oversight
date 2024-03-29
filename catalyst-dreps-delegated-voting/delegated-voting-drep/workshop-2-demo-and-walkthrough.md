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
\- 11:34 Main homepage of the GVC (Governance Voting Center) dApp\
\- 11:56 No more need for QR codes and PINs when voting\
\- 13:07 Design is finalised, but some content still to be added\
\- 13:25 dRep registration form – basic info\
\- 14:03 Your dRep profile\
\- 14:39 Tags for your interests, which will be aligned with IdeaScale tags\
\- 14:59: Feedback is welcome – but not clear where feedback should be given\
\- 15:09 Your socials links\
\- 15:31 Privacy, Terms and Conditions, KYC and Proof of Life

### Questions from Chat

**16:14 Eystein Magnus Hansen: What happens if the delegation vote and the user votes differ? Can the user’s vote override the delegation vote?**\
**Answer:** In the first iteration, it will definitely not be possible to override the dRep’s’ vote on an individual proposal that you care about. For future iterations, maybe - we need to understand why people would want to do that.

**17:42 Tomi Astikainen: Can a dRep delegate their own voting power to another dRep?**\
**Answer:** No; that breaks the purpose of dReps. \[<mark style="color:red;">Note: but see below - this is possible if you create a separate wallet.</mark>]

**18:07 Zoé Selina: Do voters have to choose between delegating and voting directly; or can they delegate a percentage of their voting power?**\
**Answer:** You cannot partially delegate. Either you delegate 100% of your voting power, or you vote yourself. Partial delegation might be possible in future, but not for this first iteration. The workaround is to have 2 wallets; one delegated, and the other for voting directly.

**19:49 Zoé Selina: Can a dRep delegate their own voting power to another dRep?**\
**Answer:** Yes, if you have two wallets. You would still need to have at least 500ADA in each wallet

**20:45 Tomi Astikainen: Can you delegate e.g. 50% to one dRep, 30% to another and 20% to a third?**\
**Answer:** Yes – this will be covered later in the slides.

**21:20 Tommy Frey: Will a downvote count as a vote?**\
**Answer:** Yes.

**21:33 Zoé Selina: There are many voices against downvoting. Why was this adopted to dReps without having the conversation?**\
**Answer:** it is currently following the original treasury paper implementation, [https://eprint.iacr.org/2018/435.pdf](https://eprint.iacr.org/2018/435.pdf) with the 3-way “yes”, “no” and “abstain”. This doesn’t mean it can’t change in the future.

**22:10 Eystein Magnus Hansen: Which wallets are supported?**\
**Answer:** We are actively working with all the community wallets that have expressed interest: Eternl, Typhon, Yoroi, Flint, Lace. It will depend which ones decide to implement it. Catalyst is being built as wallet-agnostic.

**23:40 Sebastian Pereira: If a dRep fails to vote for the minimum amount of proposals, do delegators still receive rewards?**\
**Answer:** Yes. The dRep will not, but their delegators will; and their voting power will be counted.

**24:05 Voltaire Valdellon: This delegation is Catalyst-specific, and separate from Ouroboros?**\
**Answer:** Yes, this is Catalyst-specific.

**24:21 Nori Nishigaya: Will there be support for SPOs and using the command line for delegating their voting power?**\
**Answer:** There is some tooling required on this, so it may not be possible for the MVP; but we are working with Martin from ATADA on it, who already manages many current SPO scripts, and the CLI voting tools. \[<mark style="color:red;">**Note:**</mark> <mark style="color:red;">for further info, see Martin's GitHub repo</mark> [https://github.com/gitmachtl](https://github.com/gitmachtl)]

**25:29 several commenters: Will there be an opportunity to set custom tags in your dRep profile?**\
**Answer:** Not at launch, but maybe in the future.\
**26:21 Kyle** I recommend using 2 different sets of tags – primary roles, maybe aligned with proposal categories; and ancillary/secondary skills.\
**Answer:** This is the first iteration – we will certainly want to improve.

### Presentation part 2: dRep dashboard and Voting Center

**28:12** dRep dashboard\
**28:53** Voting centre\
\- 29:05 Landing page\
\- 29:19 List of dReps – order is randomised: there is no hierarchy. Oversaturated dReps are filtered out.

### **Clarification on how saturation and reward are calculated:**

**31:16** The voting-power cap is 1% of the total _**voting**_ stake – i.e. the total amount of ADA used to vote in a particular fund. But dRep rewards are capped at 1% of the total _**delegated**_ stake. These are two different numbers.\
**For example**<mark style="color:red;">,</mark> if there is 1 billion ADA total voting stake (i.e. the total amount of ADA used in a fund), but only 100 million of that was delegated, then the maximum voting power that a dRep can have is 10 million ADA (1% of the 1 billion total), but a dRep only needs to have 1 million ADA to earn their full rewards, because it's 1% of the delegated total, 100 million, rather than 1% of a billion.\
**33:23** All these parameters will eventually be able to be changed by the community.

### **More questions from Chat**

**33:48 Henry Wang: What's the timeline for approving the applications \[**_**to be a dRep**_**]?**\
**Answer:** We're targeting voting for Fund 10, so there will have to be an earlier onboarding, to allow time for dReps to be listed and get delegation ahead of the vote for Fund 10.

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
**Answer:** Yes. It will be a CIP – I believe it is [CIP 62](https://github.com/cardano-foundation/CIPs/pull/296). We are working with the wallets to come up with the CIP. It will be publicly available, and anyone can build a similar experience, as long as they follow the same principles.

**38:58 Alejandro Gelves Gelves: Is it possible to have whale dReps, that get maximum reward even though no one delegates to them?**\
**Answer:** Yes. If you are a whale, you could create 2 wallets, register one as a dRep, and delegate to yourself. But depending how big a whale you are, you might therefore lose some of your voting influence, because as a dRep your voting influence is capped at 1%. And you would still have to meet the minimum dRep requirement of voting on 60 proposals and 20 Challenge proposals; so we would be paying a whale to work, which is not a bad thing.

**40:20 Juana Attieh: In that situation, how will your own voting power be separated from the ones accumulated by your delegators?**\
**Answer:** There’s no distinction. Your voting power is your voting power, and that's that.

**40:56 Zoé Selina: On making the vote public – are there 2 stages of voting, one for dReps and one for direct voters?**\
**Answer:** No, it is all simultaneous. While people are voting, everything is private, and nobody knows what the progress of the vote is. But after the vote, how dReps voted will be unlocked, so delegators can verify what choices their dRep made.

**42:33 Sebastian Pereira: In the case of failure by the dRep (for example, if the dRep fails to vote for enough proposals), how will the rewards for their delegators be calculated?**\
**Answer:** The dRep will not be rewarded; but the voting power will still count, and the voters will still be rewarded, so the dRep is the only one that's penalised.

**43:06 Eystein Magnus Hansen: Are there plans to track wallet voting history with the status of “yes”-voted projects; e.g did project succeed, etc?**\
**Answer**: Yes. Voting history is one of our future plans, and we hope to demo it in a future workshop like this. Obviously, it will be an opt-in; you will be able to choose whether you want your voting history to be available to you.

**43:54 Tomi Astikainen: Voter rewards are always tied to the voting power snapshot taken. Therefore it should not matter whether you "keep all eggs in one dRep basket" or split it among many - at the end of the day, your voting rewards are still the same, right?**\
**Answer:** Yes.

**44:22 Jason Toevs: What order is the list of dReps displayed in?**\
**Answer:** As mentioned earlier, it’s randomised. Oversaturated dReps are not shown initially \[<mark style="color:red;">**NOTE**</mark>: as mentioned later, you can change your filters to display them].

**44:47 Sef: How many dReps are needed? How many hours a day/week it could take to accomplish the job?**\
**Answer:** It will depend on whether you already have an audience that trust you and will delegate immediately to you. Some dReps will need to advertise a bit more; similar to stakepools.\
That’s the work to secure delegation. The other work is writing a public rationale for your vote on at least 60 proposals and 20 challenges; which should take you 5 minutes each. Then there is the time it takes to actually vote, which will depend on how much you read the proposals and how much research you do. So we imagine intensive work for a month in each Fund. But it will be different for everybody.

**46:28 Sebastian: How far are the rewards of delegators tied to the performance of the dRep? e.g. if a dRep votes for more than the minimum 60 proposals, will that increase the reward of their delegators? Will it create competition between the dReps on who can vote the most?**\
**Answer:** We haven't looked at scaling rewards based on performance; we have only set minimum requirements. But the idea is open to debate, and the community can decide to change the parameters in future.

### Presentation part 3: How to delegate

**48:09** Slide 21: On the right you can see “voting delegation”, which tells you your current state of delegation as an end user.\
**48:42** Slide 22: what a dRep’s profile looks like to a voter, and how a voter can add a dRep to their delegation card.\
**49:34** How a voter can manage the voting power they allocate to each dRep that they choose to delegate to.\
**50:06** Summary\
\- 50:18 IOG are still working on how the Proof of Life review will work.\
\- 50:56 Delegation values reset after each fund – this is as a safeguard to avoid concentration of power, but it’s a parameter that the community could decide to change.

### More questions from Chat

**52:32 Darlington Wleh: Will the open APIs be published on the same timeline as this UI?**\
Answer: Yes, the plan is to release them together, aligned with Fund 10.

**53:20 Eystein Magnus Hansen: Is a dRep’s voting power shown to the delegators?**\
**Answer:** Yes. Obviously, it depends on timing: it will change as we get closer to the snapshot moment where the total delegated amount is confirmed.

**54:21 Kenric Nelson: If a dRep's delegation goes over 1%, can people still delegate to them?**\
**Answer:** We will not stop them, but we will give a warning that they are delegating to someone who's already oversaturated and they will lose their voting rewards as a result. If you still want to delegate, we can't stop you, and we shouldn't stop you.\
**Kenric Nelson:** Part of why its important to allow people to delegate to oversaturated pools, is to protect against the following type of scenario: A whale saturates a dRep and then at the last minute removes all of their delegation, leaving the dRep without delegation.

**55:10 Voltaire Valdellon: It was mentioned previously that the dReps in the top 150 of voting power would receive rewards. Is this in addition to or separate from the Direct Voting requirements?**\
**Answer:** It’s separate – direct voting is different from delegated voting, and they are separate.

**55:43 Zoé Selina: Why are oversaturated reps not shown? Oversaturated stake pools are always shown, and it's your personal decision whether you want to go into it or not.**\
**Answer:** It’s only initially that they do not display; if you change your filter, they will show. So we are not trying to hide the information; we are just making it harder for users to waste their voting rewards.\
A dRep cannot have more than 1% voting power; it’s a safeguard to prevent power concentration. Delegating to a dRep who has reached that limit would be a wasted vote, both for rewards and for your vote – you might as well vote directly or delegate to someone else.

**57:54 Joanna: Can every wallet choose to delegate their entire voting power to 10 different dReps? Or do they have to allocate their voting power \***_**across\***_\*\* 10 different dReps?\*\*\
**Answer:** You cannot partially delegate your voting power. So when you delegate, you delegate all your voting power; and you can delegate it to up to 10 dReps.\
**58:27 Joanna:** But then, if two different dReps voted on the same proposal, that's doubling my voting power, whereas now I can only vote once on one proposal?\
**Answer:** You have a weight attached to your voting power – see the percentage sliders shown on slide #24. The slider will move dynamically; you might want to give 90% to one dRep, and 10% to another. It's your prerogative.

**59:22 Alejandro Gelves Gelves: Once a dRep is saturated, what prevents more people delegating to them?**\
**Answer:** To reiterate – nothing. But they will see a warning that they are about to waste their voting power.

**59:47 Rodolfo Miranda: Are the past votes of a dRep’s wallet public or private?**\
**Answer:** For votes from before you became a dRep: one requirement to become a dRep is that you need to have voted in a previous fund. To maintain privacy e.g. on how much ADA you personally hold, you can create a new wallet as a dRep; and we would validate that you voted in a previous fund via the proof of life review, a private meeting which we still need to define. For votes in future Funds, we want to let users see a dRep’s previous voting history, so we are planning that for a future iteration.\
**In chat from Harris Warren, IOG:** As long as you are a registered dRep your votes will be public. If you delete your dRep profile then your votes will be private by default.

**1:02:07 Tomi Astikainen: \_\*\*\*\***_\*\* Can \*\*_**\*\*\*\***\_\*\* whales have multiple wallets and get rewarded multiple times?\*\*\
**Answer:** For voter rewards, it will be the same as if they voted from one wallet with all their ADA in it, because that's how voter rewards are calculated. If they were to try to become more than one dRep, they would be filtered out at the Proof of Life stage.

**1:02:52 Eystein Magnus Hansen: Will it be frowned upon for dReps to make public how they plan to vote?**\
**Answer:** It’s a matter of transparency. A dRep says in their profile what types of projects they will vote for, and people will delegate to them based on that. If they then vote for something different, that could cause problems with people who delegated to them. But their written rationales should explain why they voted as they did. People need to know they can trust you as a dRep to use _their_ voting power the way you said you would.

**1:04:22 Jason Toevs: Are the delegated wallet addresses made public along with the dRep votes after the Tally?**\
**Answer** If you're voting directly, your vote is kept private. If you've delegated, your wallet is not casting the vote; the dRep is doing it on your behalf, and their wallet is made public.

**1:04:47 Alejandro Gelves Gelves: Is there a plan to be more transparent in the voting results? A dashboard that shows all projects and their upvotes and downvotes. and maybe also the wallets? How do we know that our votes, and dRep votes, were actually counted? Shouldn’t this be automated and perhaps real-time?**\
**Answer:** Yes. We need to provide better tooling to build more transparency into future versions. The past history of the votes that have been cast will all become available. Our goal is to give you the tools to verify the results yourself.

**1:06:33 Tomi Astikainen: Can a voter whale register ten wallet addresses, vote for (and saturate) ten different dReps and get 10 x rewards?**\
**Answer:** No, because voter rewards are based on the total ADA you have. So whether you vote with all of your ADA in one wallet or split it in 10, the actual amount doesn’t change.\
**Later answer 1:09:01:** The whale would have a reduction in voting rewards if they oversaturate a dRep. So let's say one whale has 2% voting power, and they delegate it all to one dRep - they slash their voting rewards in half. So they could decide to have two wallets, do 1% to one dRep, and 1% to another, and get their full reward. But they could equally get their full reward if they just voted directly without using a dRep. So there isn't any actual increase in monetary gain.

**1:07:38 Christophe Garant: Will voting tools make it easier to 1) vote/delegate with multiple wallets, 2) create a voting list easier, select multiple proposals, sortable, smart query?**\
**Answer:** Yes, we hope to build all these functionalities, though not for Fund 10. We plan for batch voting, advanced filters and more. But we want to be realistic and make sure we have a usable experience ready for Fund 10. Once it's out there, we will iterate with the community.

**1:09:39 Tommy Frey: Keeping in mind the minimum numbers of PA and VPA reviews desired - what number of dRep votes per proposal is desired?**\
**Answer:** That's not a parameter that we've discussed. For the first iteration, a good success metric could be simply that 20% of all voting stake was delegated. But we can’t predict how people will behave; and we want the community to also define some of these metrics.

**1:11:11 Tommy Frey: And what is the total dRep budget?**\
**Answer:** The dRep rewards come out of the voter reward pot. A percentage of each fund goes to those rewards, and the dReps will be coming out of that percentage. The total amount an individual dRep can earn will be $3,060. I can't remember why we settled on that amount – I think there’s a percentage max to go with the total fund pot, versus the percentage of how much is available to voter rewards. But rewards can be discussed and changed in future.\
**1:12:21 Tommy Frey:** I was trying to find out the number of dReps that you want. Rewards are only a part of the budget – there is also the cost of developing a software program, the API, doing these workshops. Why is Cardano Foundation so interested in liquid democracy that you're putting in how much money into it? As a business person, as an investor - what's the total budget earmarked for this project?\
**Answer:** I don’t have the figures to hand. The reason for it is the broader plan that we have for governance for Cardano – we believe delegation is important, and we hope the experiment will show we are correct.

**1:14:08 Alejandro Gelves Gelves: Is it possible to have “dead” voting power - dReps that do not review, and voters who delegated to them but do not switch, since they still get rewarded?**\
**Answer:** As a direct voter you only need to cast one vote to get your full voting reward. \[<mark style="color:red;">**Note:**</mark> <mark style="color:red;">misspeaking? In F10 there are minimum requirements for direct voters to get rewards - they must vote on at least 30 proposals and 10 challenge proposals. See next question.]</mark> But with a dRep, if they don't cast any vote, do the delegates get the reward? I'm not sure they do. I think it's just a mechanical rather than a philosophical rule. But we need to check.\
<mark style="color:red;">**ACTION ITEM:**</mark> Danny and Jack to take this question back to confirm.

**1:15:05 What is the minimum requirement for the direct voters in order to be eligible for the voting rewards?**\
**Answer:** In Fund 10, it’s 30 proposals, and 10 Challenge proposals. If you vote on fewer, your voting power will still count; you just won't get any voter rewards. If you delegate to one dRep, you get your full voting reward. So we would encourage voters who are short of time to delegate their voting power.

**1:16:22 Christophe Garant: Will dRep wallets be kept private?**\
**Answer:** No, they are public, and we show them in the dRep’s profiles.

**1:16:37 Tommy Frey: Can SSI be used as an experiment for this?**\
**Answer:** Yes; we are considering it – but not for F10. There's also a concurrent effort under way to pilot SSI with VPAs.

**1:17:29 Kyle Wood: Will there be any restriction on dReps voting on their own proposals?**\
**Answer:** This was discussed in the first workshop in June \[see [**here**](https://quality-assurance-dao.gitbook.io/community-governance-oversight/dreps-delegated-voting/delegated-voting-drep/workshop-1)]. Originally, we had said no; and then someone came up with a good example of why you should be allowed to. We spoke to the research team at IOG and realised it made sense; so yes, you can vote on your own proposals. But you should declare your intentions openly in your profile, so people that delegate to you know your intention.

**1:18:57 Can every wallet delegate to 10 different dReps?**\
**Answer:** Yes. If you have a wallet, it doesn't matter what the wallet provider is - anyone can delegate, as long as the wallet supports the new CIP 62 feature which will be coming out with Fund 10. <mark style="color:red;">\[</mark><mark style="color:red;">**NOTE:**</mark> <mark style="color:red;">This answer may not address the question that was asked]</mark>

**1:19:50 Alejandro Gelves Gelves Is there a queue that is recorded when you delegate to a dRep, which remembers who delegated first and last? If I delegate when saturated and then some people leave, would I be first in line to be included in rewards?**\
**Answer:** It all works at snapshot. Whatever was in the past or may happen in the future does not apply. We will be able to show you a continuous snapshot of what your current voting power is. There still might be a 24 hour delay; but ultimately, the calculations happen at snapshot. <mark style="color:red;">\[</mark><mark style="color:red;">**NOTE:**</mark> <mark style="color:red;">This answer may not address the question that was asked]</mark>

**1:21:23 Tomi Astikainen: What are the implications if I am a whale, and I create 100 different wallets and hire 100 people to do the dRepping for me; they do the PoL but essentially it's one big team against the world?**\
**Answer:** The “frontman” dRep would have to identify themselves during Proof of Life and have control of that wallet; so they would have to have control of that proportion of a whale's wallet. So that whale would therefore have to trust that frontman, which is probably unlikely. But we should always look at edge cases as those are where attacks happen.\
<mark style="color:red;">**ACTION ITEM:**</mark> Question noted: to be discussed further.

**1:23:06 Andreas Sosilo: Are we no longer using the Catalyst voting app in Fund 10?**\
**Answer:** Our goal for Fund 10 is for dReps to be able to use it to vote and to manage their profiles; and for delegators to use it to find dReps and delegate to them. The third element is the active voter – for them, the Catalyst voting app, and QR and PIN codes, will remain the primary voting method in F10, unless they are brave enough to risk a beta app. We don't want to stop anyone artificially from using the app; but we are not recommending general public use for F10. So the main focus of the Voting Centre for F10 is for dReps, and we hope it will be a real alternative for everyone in F11.

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

{% embed url="https://youtu.be/bH1vqoyNGjM" %}

0:00 - Preamble

### Presentation

{% hint style="info" %}
**Note :** Images of each Slide from the presentation are reproduced here for context
{% endhint %}

#### 04:17 - Slide Presentation - Jack Briggs

<figure><img src="../../.gitbook/assets/Slides-01.png" alt=""><figcaption></figcaption></figure>

#### 05:17 - Welcome to another experiment

<figure><img src="../../.gitbook/assets/Slide-02.png" alt=""><figcaption></figcaption></figure>

#### 05:49 - Things may break

<figure><img src="../../.gitbook/assets/Slide-03.png" alt=""><figcaption></figcaption></figure>

#### 06:05 - Agenda

<figure><img src="../../.gitbook/assets/Slide-04.png" alt=""><figcaption></figcaption></figure>

#### 06:38 - Recap

<figure><img src="../../.gitbook/assets/Slide-05.png" alt=""><figcaption></figcaption></figure>

#### 08:34 - What is Liquid Democracy ?

<figure><img src="../../.gitbook/assets/Slide-06.png" alt=""><figcaption></figcaption></figure>

#### 09:09 - Why Delegation and dReps ?

<figure><img src="../../.gitbook/assets/Slide-07.png" alt=""><figcaption></figcaption></figure>

#### 10:36 - dRep Registration - Abhiroop Sharma

<figure><img src="../../.gitbook/assets/Slides-08.png" alt=""><figcaption></figcaption></figure>

#### 11:27 - Voting Center

<figure><img src="../../.gitbook/assets/Slides-09.png" alt=""><figcaption></figcaption></figure>

#### 12:21 - Vote as an expert

<figure><img src="../../.gitbook/assets/Slides-10.png" alt=""><figcaption></figcaption></figure>

#### 12:52 - Basic Information

<figure><img src="../../.gitbook/assets/Slides-11.png" alt=""><figcaption></figcaption></figure>

#### 13:47 - Profile

<figure><img src="../../.gitbook/assets/Slides-12.png" alt=""><figcaption></figcaption></figure>

#### 14:19 - Expertise / Interests

<figure><img src="../../.gitbook/assets/Slides-13.png" alt=""><figcaption></figcaption></figure>

#### 14:53 - Socials

<figure><img src="../../.gitbook/assets/Slides-14.png" alt=""><figcaption></figcaption></figure>

#### 15:27 - Privacy

<figure><img src="../../.gitbook/assets/Slides-15.png" alt=""><figcaption></figcaption></figure>

#### 15:50 - Submit Application

<figure><img src="../../.gitbook/assets/Slides-16.png" alt=""><figcaption></figcaption></figure>

### Questions I

#### 16:34 - Question - What does it mean for a wallet address to remain fixed ?

Allison Fromm

**Answer** - It's the wallet which you are voting with. So we use the wallet to link your voting power to you, regardless of whether you are an active voter, or a passive voter, or active dRep.

#### 17:21 - Question - Is the right to be forgotten universal ?

Allison Fromm

**Answer** - For public data? Yes. We obviously have to work through certain other edge cases and elements. And this is still MVP (minimum viable product), our first version. \[...] we will certainly be adding more features.

#### 17:51 - Question - Will this be Open Source ? Can others create an alternative front end ?

Allison Fromm

Answer - So to your second question, yes. We will be releasing open API documentation as well as package along with it where you should be able to build a similar GVC voting centre experience. Whether or not the voting centre itself will be open sourced? I'm not sure.

#### 18:31 - Question - Does the address become a public metric - so everyone will know how much ADA is in my wallet ?

Allison Fromm

Answer - Yes, I think essentially, that's part of becoming a dRep. \[...] that information will become publicly known, how much ADA you have in your wallet because your voting power will be known.

#### 20:13 - GVC - Governance Voting Center acronym

Answer - GVC stands for Governance Voting Center

#### 20:51 - dRep Dashboard

<figure><img src="../../.gitbook/assets/Slides-17.png" alt=""><figcaption></figcaption></figure>

#### 21:49 - The new voting center

<figure><img src="../../.gitbook/assets/Slides-18.png" alt=""><figcaption></figcaption></figure>

#### 21:55 - Delegate your voting power to dReps

<figure><img src="../../.gitbook/assets/Slides-19.png" alt=""><figcaption></figcaption></figure>

#### 22:28 - Experts helping to grow Cardano

<figure><img src="../../.gitbook/assets/Slides-20.png" alt=""><figcaption></figcaption></figure>

#### 22:54 - List of dReps

<figure><img src="../../.gitbook/assets/Slides-21.png" alt=""><figcaption></figcaption></figure>

### Questions II

#### 23:06 - Question - Will delegators to a dRep remain anonymous ?

Allison Fromm

Answer - Abhiroop Sharma - I believe when you delegate you delegate with your voting key. \[...] I believe your delegation is not anonymous. Daniel Ribar - It would work similarly to when you're staking because it's an on chain event. \[...] What is visible on chain is visible to everyone else.

#### 23:54 - Question - As a dRep can I identify the wallets that are delegating to me ?

Answer -

#### 24:09 - Question - Would the dRep be exposed to any regulatory issues around KYC (knowing your customer) regarding the wallets that are delegating.

Allison Fromm

The second question, and I know this is a regulatory mess. \[...] would \[the dRep] be exposed to any regulatory issues around knowing your customer (KYC), regarding the wallets that are that are delegating. And I know I am sure you can't answer that question but I wanted to raise it as something \[to] think about \[...] Because, as an American, for example, can I transact with somebody who's located in in Cuba ?

Answer - Daniel Ribar - Good question. So, as you said, I don't think we're qualified just to give a good answer yet. But we're taking notes, and putting it on the list to discuss. As you said, we're doing something that hasn't been really done before. So we're trailblazing a bit ahead of any regulation or legal framework.

#### 25:26 - Question - As a dRep should I make a new QR code ?

Tevo Saks

Answer - Abhiroop Sharma - The short answer is no. The idea is that you would connect your wallet using the "Connect wallet" option on top. Which would link to one of the supported wallets at launch. The idea is to move away from the QR code, PIN code style of operation, and a more fluid experience overall.

#### 26:28 - Question - If I use the same wallet that I have been using (for voting) I don't have to re-register ?

Tevo Saks

Answer - Abhiroop Sharma - You won't have to re-register. There will be a call to action on the site for you to register to vote.

#### 26:54 - Question - I thought this was going to be part of Lace ?

Steve Lockhart

Answer - Daniel Ribar - I think it's important to just realise that Catalyst is being built wallet agnostic. We're inviting all the wallets that are eager and willing to participate, which could include Lace or a number of others. We have a working group that meets regularly on a bi weekly basis with eternl. Lace, Flint, Yoroi etc, because essentially, these efforts are open to all the community.&#x20;

#### 27:56 - Question - How easy will it be for a group to handle a dRep account ?

Answer - Abhiroop Sharma - \[There is nothing] stopping two users from knowing the same wallet details. So you could, in theory, have multiple people share a wallet. But \[...] there's no facilitation as such, for the DAP, it's always just one connected wallet, regardless of how many humans are behind that wallet.

#### 29:07 - Question - Is there a section in the GVC (Governance Voting Center) for users to skip the dRep delegation ?

Daniel Ribar - I would assume that \[this question] maybe related to the flow, what is the first thing that people will see when they land on the GVC?

Answer - Abhiroop Sharma - If we go back to the homepage, the first thing \[the user does] is to register to work. After \[the user has] registered and connected \[their] wallet, then \[they] can delegate. So the "Register to work" button would show up immediately after \[a user] connects. That's the first thing \[a user does] once \[they are] registered, then \[they] can delegate \[their] vote or vote \[themselves].&#x20;

If you try to do those action before registering, we will of course give you a warning \[to] go back and register to vote first \[...]

#### 30:07 - Question - I read somewhere that future dReps had to vote in Fund 8 in order to actually become dReps ?

Answer - Jack Briggs - If you participate in Fund 9, that will make you elegible. So you're correct in the fact that you \[are required] to vote in a previous Catalyst voting round.&#x20;

If you have a new wallet connected as a dRep, your voting history won't be on that and we will \[review / verify] during the proof of life \[...] to make sure you're real \[...]

#### 31:12 - Question - At that point (after proof of life) you can still create a new wallet

Answer - Jack Briggs - Yes

#### 31:21 - Question - So we would have to identify our wallets as part of that proof of life ?

Answer - Jack Briggs - Yes. We haven't worked out the exact ask of you on this one. \[...] we need to make sure it's \[...] publicly safe to do that with us. Doing a proof of life will be a private experience, it won't be public.

#### 31:55 - Question - Do we have any rating for each dRep after each Funding round ?

Answer - Jack Briggs - I don't think the functionality exists yet. \[...] But in terms of reputation, \[...] we do have as part of your role as dRep \[a requirement] to provide rationale for each way you voted in a funding round that will be publicly available.

Not just to the people that delegate to you, primarily it is for them, but also for your wider profile \[...]

#### 32:47 - Question - Currently Stakepool Operators (SPOs) have a special process to register themselves in the Catalyst Voting App using the CLI voting tools. Will a SPO be able to connect with their pledge so it counts towards voting ?

Answer - Abhiroop Sharma - \[...] if you if you could delegate to a software wallet, you could connect the software wallet. But there is no special process for SPO's currently. We are actively working internally to figure out if there is a way to extend delegations to SPOs in a future iteration.

Daniel Ribar - To that we're also working very closely with Martin \[Lang] from ATADA team that caters to a lot of CLI (Command Line Interface) and SPO related voting tools and manages a lot of those libraries. ([https://github.com/gitmachtl](https://github.com/gitmachtl))

#### 34:13 - Question - How public will Proof of Life data be and does it comply with all the Right to be Forgotten legislation ?

Answer - Jack Briggs - Yes, it's still a process that we're trying to map out, there might be some level of KYC (Know Your Customer). But ultimately, it will follow GDPR rules ([General Data Protection Regulation](https://gdpr-info.eu/)) and other applicable laws for data.&#x20;

So yes, there'll be a right to be forgotten in some form. But as Abi said, we need to work through some of the nuances with blockchain \[...] We will consult with every dRep here about the Proof of Life process to make sure that everyone's comfortable and \[to resolve] any questions before we embark on it.

#### 36:26 - An individual dRep profile

<figure><img src="../../.gitbook/assets/Slides-22.png" alt=""><figcaption></figcaption></figure>

#### 37:04 - Voting delegation

<figure><img src="../../.gitbook/assets/Slides-23.png" alt=""><figcaption></figcaption></figure>

#### 37:34 - Add another dRep

<figure><img src="../../.gitbook/assets/Slides-24.png" alt=""><figcaption></figcaption></figure>

#### 38:13 - Your voting power has been delegated

<figure><img src="../../.gitbook/assets/Slides-25.png" alt=""><figcaption></figcaption></figure>

#### 38:38 - Summary

<figure><img src="../../.gitbook/assets/Slides-26.png" alt=""><figcaption></figcaption></figure>

### Questions III

#### 41:37 - Question - What if a dRep votes at random without understanding what the proposal is about ?

Answer - Jack Briggs - Yeah, it's a good it's a good question. \[...] I think ultimately it comes down to reputation and that dRep letting down the people that delegated to them.&#x20;

And \[...] it will hopefully be evident through the rationale that \[the dRep] needs to provide. As you said, importantly, that might trigger \[the possibility] that they may not get recognition in the future, because they behaved poorly in the first time.&#x20;

\[...] I do think reputation metrics will come into play in the future, \[so] it's a bit more easy and transparent for people to see \[...] It might be a bit crude in its first iteration.

#### 42:39 - Question - Is there any public testing ground for dReps ?

Answer - Daniel Ribar - I did allude that this is a test in a way.

Abhiroop Sharma - \[...] we are looking to have a test environment but we currently think that it will be only available by the time \[the GVC] is launched anyway. So as Daniel was saying, we are all in a giant experiment. \[...] in the a future iteration we may look at having a pre beta version of the app available which is isolated from production.

#### 43:51 - Question - Does the GVC (Voting Center) link the wallet address of every delegator to the profile they create on the GVC ?

So if the delegator uses their real name does that mean they are doxxing their wallet address ?

Answer - Abhiroop Sharma - Delegators don't need to create a profile. Only the dReps need to create a profile. Delegators will just connect their wallet and delegate. They have no additional user data stored on our site.

#### 44:49 - Question - Could we have a private dRep, in the sense it isn't shown on the list ? For example I may want my family to delegate to me but I do not want others to do so.

Answer - Abhiroop Sharma \[...] I was alluding to this a bit earlier \[...] wallets could create an experience for you to help you delegate from one account to other accounts.&#x20;

Other than that, I'm hoping that in our documentation, we can provide a guide. But unfortunately, you know, you still need to have the technical knowledge to submit a transaction to a blockchain \[using] CLI (command line interface) or an advanced method.

#### 46:11 - Question - But there is a Cap right ? \[...] no more than 1%?

Steve Lockhart

Answer - Abhiroop Sharma - There is a cap. Yes

#### 47:46 - Delegation snapshot and limits

Steve Lockhart - \[there is] 3 billion ADA currently registered to vote on Ideascale ?&#x20;

So that would imply \[...] that the 1% cap would be somewhere above 30 million, right?

Daniel Ribar - So, Yes. The cap doesn't limit the number of wallets that delegate to you. You can over delegate to someone. But \[that] diminishes the rewards and does not increase the voting power. \[there are] saturation points.

Steve Lockhart - That's something that the delegating voters should know \[if a dRep] is over the 1% ?

Daniel Ribar - I think that should be visible \[...] because we are also implementing as a part of the iteration a continuous snapshot feature.

Abhiroop Sharma - \[...] they'll be a warning if you're trying to delegate to an oversaturated dRep. But we will not stop you. \[We will just] warn you that you will get slashed rewards because you are delegating to someone who is over saturated.

Daniel Ribar - \[This is] definitely \[about] education. \[...] the user interface indicates that the voting power is no longer tangible. If you delegate to a dRep which is currently saturated you are erasing your voting power because it wouldn't have an effect.&#x20;

#### 50:24 - Question - Is a \[transaction] fee charged to delegators every time they set or change a dRep in the voting center ?

Answer - Abhiroop Sharma - I believe so. Delegation is on chain \[so would attract a transaction fee].

Jack Briggs - You could build up your shortlist of dReps and change them as much as you want before you've confirmed your delegation.&#x20;

Daniel Ribar - Every time you make a transaction on a main chain that will incur transaction costs in order to move to that ledger.

#### 51:50 - Question - Could you elaborate on what is the minimum amount of delegated ADA that a dRep needs to have to be active ?

Answer - Jack Briggs - The dRep rewards are based on their on the percentage they have \[of] delegated stake.&#x20;

So let's just look at some easy numbers, if we had 1 billion total voting stake, you would need 10 million to have your 1% in total voting stake. That means about 100 million of that 1 billion total voting, only 100 million of that was delegated, you only need to have 1 million to only a full reward. So that \[is] how it favours the early group of delegators because you don't need to have 1% of the total voting stake to earn your full reward.&#x20;

#### 53:21 - Question - When is the total delegated stake number calculated ? At what point in the process ?

Allison Fromm&#x20;

Answer - See below

#### 53:37 - Question - Could you clarify the difference between staked ADA and delegated ADA ?

Answer - Jack Briggs - Total voting stake. The ADA used to vote. So in Fund 9, for example, there might be 1 billion ADA used as voting weight to vote on proposals as a whole.&#x20;

Now delegated voting stake is the proportion of that billion that was used in delegation.&#x20;

So that might be 100 million, or might be the 50% of people that delegated it might be 500 million.&#x20;

That's how the rewards are calculated. Your rewards are 1% of delegated voting stake. Your voting power, though, as a dRep is based on the whole.

#### 54:42 - Question - What voting stake is determined at the time of this snapshot ?

Answer - Jack Briggs - \[The voting stake is determined at the time of the sanapshot] because then it is locked, nothing can change.

Daniel Ribar - \[...] so whatever is eligible \[...] is then included in a snapshot.&#x20;

#### 55:19 - Question - Timing - when is the total delegated vote stake calculated ?

Allison Fromm

Same question about the timing. \[...] the total voting stake is determined at the snapshot. That makes sense.&#x20;

But when is that total, delegated stake number calculated? Because \[...] everybody has to make their delegations selections before the snapshot?&#x20;

Jack Briggs - Correct.&#x20;

Allison Fromm - And so the voting power is determined also at the snapshot. Yeah, that makes sense. \[But] we won't know, then what we need as a maximum until after it's too late to do anything about it, basically ?

#### 56:12 - Question - Saturation concept - Saturation is based on voting stake or delegated stake ?

Answer - Voting Stake.

Allison Fromm - But I'm confused that about the saturation, you wouldn't be able to know if you're saturated, until you know, the total voting state.

Abhiroop Sharma - I could help answer that. We are going to implement a process called continuous snapshot.&#x20;

We will be getting from the system to show you \[the status] before the snapshot. So it won't be a surprise to you at snapshot. But it may not be perfectly aligned. Because there's a lag between the delegation and the voting power calculation. There might be a 24 hour lag or something, but you will still get an approximate idea of where you stand.

#### 57:12 - Question - This effects more the voter delegating to you ?

Answer - Abhiroop Sharma  -Nobody can stop \[anyone] from delegating to you from a blockchain perspective. What we are doing with the dRep experience is trying to promote delegation to a set of publicly selected dReps. But nothing stops \[anyone] from delegating to arbitrary wallet on the chain.

#### 58:28 - Question - Lets say I am a dRep, I have a pretty average group of delegators and I am well below saturation. But right before the snapshot, a whale decides to delegate to me, and it puts me over the saturation

Allison Fromm

Answer - Abhiroop Sharma  - It doesn't make a difference to you. It makes a difference to the Whale. He or she loses their voting power. It doesn't affect anyone else.

#### 1:01:49 - Question - 1 Billion voting stake. As a dRep your stake is maxed at 1% what levels will you need ?

Answer - Jack Briggs - If you are the 1% cap \[...] you're pretty guaranteed your full reward.

#### 1:04:18 - Question - So these levels would enforce a cap on the number of dReps ?

Answer - Jack Briggs - Yes. So it's a good question. There is a cap \[...] in terms of the dReps that will get rewarded.&#x20;

Philip Lazos - To be rewarded somebody needs to be in the top 150 directs in terms of the delagation they have received. Once they've cleared this mark and \[...] they are in the top 150 then they will get rewarded proportionately depending on the delegation from zero to around $3,000, which is reached, I think when the relegation reaches 2% of the delegated stake.&#x20;

Basically, they'd have to be in the top 150 To be eligible to get rewarded. And then they'll get proportionately zero up to 3000, depending on the percentage of the delegates stake.&#x20;

#### 1:06:38 - Question - The voting rationale is not the main aspect ?

For example, you are a dRep as long as people delegate enough to you ?

Answer - Jack Briggs - I think you're a dRep \[whether] you have one delegation or 1000s. You're \[still] involved in that way in the ecosystem.


# Phase 5 Trinket Swaps

## Preface

All the way up until the [assumptions](#Assumptions) section is really a preface, so I guess this is the preface's preface.

As of now, there is no TLDR to this guide and reading any one part of the guide without knowledge of the rest is pretty useless.  This guide is also 100% minmaxing and will suggest a playstyle about maximizing the upper limit of hunter DPS.  **It may suggest behaviors that may lower your average parse as long as they increase the upper bound of the damage you may be able to do given luck with FD resists.**

It also does not attempt the "how" of trinket swapping.  [Skinnay's Renataki's guide](https://gist.github.com/skinnay-dev/0ce6448cc5f9e74336a096eb60708a99) has the macro which I use and recommend.  Addons like trinketmenu and itemrack have functionality to do this, but as of now seem inconsistently delayed.

## Trinkets

| Name | Effect | Dur. | CD |
|-|-|-|-|
| [Badge of the Swarmguard](https://classic.wowhead.com/item=21670/badge-of-the-swarmguard) | _(~80%)_ chance on hit to give 200 armor pen stacking up to 6 times | 30s | 3m | 
| [Jom Gabbar](https://classic.wowhead.com/item=23570/jom-gabbar) | +65 ap and an additional +65 AP every 2s (avg. 325 AP) | 20s | 2m |
| [Earthstrike (ES)](https://classic.wowhead.com/item=21180/earthstrike) | +280 AP | 20s | 2m |
| [Devilsaur Eye (DE)](https://classic.wowhead.com/item=19991/devilsaur-eye) | +150 AP and 2% hit  | 20s | 2m |
| [Renataki's Charm](https://classic.wowhead.com/item=19953/renatakis-charm-of-beasts) | clears the CD of Aimed and Multi shot | | 3m |
| *Passive Trinkets:* | | | |
| [Blackhand's Breadth (BHB)](https://classic.wowhead.com/item=13965/blackhands-breadth) | Passive: +2% crit | | |
| [Drake Fang Talisman (DFT)](https://classic.wowhead.com/item=19406/drake-fang-talisman) | Passive: +56 AP, 2% hit, 1% dodge | | |
| [Royal Seal of Eldre'Thalas (RS)](https://classic.wowhead.com/item=18473/royal-seal-of-eldrethalas) | Passive: +48 ranged AP | | |

_This guide will use BHB and RS as passive trinkets.  If you have been lucky enough to get DFT, you can assume the math here holds if you just swap out RS for it.  **However,** if you are using the %hit from DFT to get ranged hitcap, then the math here may not work for you since it is largely about maximizing your active trinket usage and as such you will have RS/DFT on for as little time in a fight as possible._

## Context

In phase 4, hunters only had access to 2 DPS trinkets (excluding [Devilsaur Tooth](https://classic.wowhead.com/item=19992/devilsaur-tooth)): [Devilsaur Eye](https://classic.wowhead.com/item=19991/devilsaur-eye) and [Renataki's Charm](https://classic.wowhead.com/item=19953/renatakis-charm-of-beasts).  The optimal opening was to use Devilsaur Eye and delay the use of haste abilities like Rapid Fire and Berserking such that the shared cooldown put on Renataki's Charm was up. This allows you to hast a third Aimed Shot from the Renataki's reset.  After this opener, you would Feign into passive trinkets.  Below is a timeline of skill usage and some further explanation.

![Renataki's Opener Timeline](media/rena_openner.png)

`Auto - DE and Aimed - rotation until Aimed is off CD - RF and Aimed - rotation until Aimed is off CD - Aimed - use Renataki's - FD and swap to passive trinkets - Aimed - Multi - Auto - into rotation.`

Using DE puts Renataki's on a 20s CD.  We delay using Rapid Fire so that it hastes 3 Aimed Shot (from the Rena reset). There is a 3 second timer after FD in which you cannot Auto Shot.  Because of this, if you FD and cast Aimed Shot after it and the Aimed Shot is hasted, you should cast Multishot immediately following it since you still won't be able to Auto.

### Phase 5

This phase introduced 3 new active trinkets: [Badge of the Swarmguard](https://classic.wowhead.com/item=21670/badge-of-the-swarmguard), [Jom Gabbar](https://classic.wowhead.com/item=23570/jom-gabbar), and [Earthstrike](https://classic.wowhead.com/item=21180/earthstrike).  _If you are a new hunter and have not yet gotten  [Devilsaur Eye](https://classic.wowhead.com/item=19991/devilsaur-eye), you should strongly consider taking [Devilsaur Tooth](https://classic.wowhead.com/item=19992/devilsaur-tooth) instead.  They are rewards from the same quest, you may only choose one, and Tooth is a BiS trinket for BM hunters in TBC._

These new trinkets are far stronger than anything we've had before but also a pain in the ass to reason about.

## Mechanics

Most trinkets in classic put other equipped trinkets on a `max(10s, duration)` cooldown when used.  [Badge of the Swarmguard](https://classic.wowhead.com/item=21670/badge-of-the-swarmguard) is a relevant exception to this; it does not put other trinkets on cooldown.  

### Feign Death (and resists...)

Swapping trinkets during a fight is done via Feign Death.  Trinkets are put on a 30s CD when they are initially equipped.  Feign Death renders hunters unable to auto attack for 3 seconds afterwards and so it should be timed with your Aimed Shot cooldown so as to not loose damage.  For the reason described in the [phase 4 Renataki's opener](#Context) above, if you have a haste effect active when you `FD -> Aimed` then you should immediately cast Multishot afterwards if the cooldown is up.  

Feign Death can be resisted by any mob within 40 yards of you.  A single resist will render you unable to swap trinkets and be a DPS loss.  Taking spell hit or the Improved Feign Death talent will lower the chance but will hurt your normal damage (though spell hit weapons can be swapped just before FD and immediately swapped off before aimed shot if you are feeling particularly sweaty).  This guide will attempt to give the best swap rotations for the best parses and thus will not consider whether chained FDs lower your average parse due to FDs.

#### Single Swapping

Up until now, we've only had 2 active trinkets to double swap into passives after they have been used.  Since Renataki's reset our Aimed cooldown, it was easy and natural to simply use it, FD, swap to passives, and then Aimed Shot.  With the introduction of more trinkets than we can hold in phase 5, the best strategy for trinket swapping duration-based trinkets becomes single swaps.  

In an example rotation using Jom, ES, and DE, we would start the fight with Jom and ES on:
- We use Jom and begin our rotation.  
- As soon as Jom is done, we `FD swap Jom into DE, use ES, cast Aimed Shot`.  This gets the DE's 30s swap cooldown overlapping with our usage of ES.  ES will end and both FD and DE will have 10 seconds left on their cooldowns.  
- As soon as they're up, we `FD swap ES into BHB, use DE, cast Aimed Shot`.  
- Once FD CD is back up, if there is a decent bit of time left in the fight, we'd FD DE into our other passive trinket.  

In total, 1m20s elapse from the start of the fight to the moment we are in double passive trinkets.  If we double swapped, it would take 1m40s to get from the fight beginning to double passives.  Single swapping requires more `(n - 2)` swaps per trinket whereas double swapping requires `(n - 2) / 2` rounded up.  As said above, this dramatically raises your chance to be resisted-- however.  Single swapping is actually safer since you ignore the resist, cast your prepped trinket, and double swap the next time your FD CD is up. 

### Rotation-based Variance

[Earthstrike](https://classic.wowhead.com/item=21180/earthstrike) and [Devilsaur Eye](https://classic.wowhead.com/item=19991/devilsaur-eye) are constant AP gains and so are easy to calculate the DPS gain from.  [Jom Gabbar](https://classic.wowhead.com/item=23570/jom-gabbar) and to a lesser degree (due to its high proc change) [Badge of the Swarmguard](https://classic.wowhead.com/item=21670/badge-of-the-swarmguard) are slightly harder to math about since they're less effective in the earlier parts of their duration.  [Renataki's](https://classic.wowhead.com/item=19953/renatakis-charm-of-beasts) value varies wildly depending on what point of your rotation it is used in.

Attempts to solve for optimal active trinket rotation in the past are few and have mostly worked by amortizing the benefit of the trinket without concern for the hunter's rotation.  While I am hugely appreciative of any well done math, I'm basically writing this guide because I'm not confident in the aforementioned approach given how rotation dependent several mechanics are (namely Renataki's and FDs needing to line up with Aimed CD).

### Rotations

This guide will include math for the normal ranged rotation and max weave rotation trinket usage.  Normal weaving _should_ see similar trinket usage as the normal ranged rotation if your weaves do not significantly delay your ranged rotation (sub 2.6 on Ashjre'thul).  _If you are still cursed with Rhok or an Ashjre'thul replacement from AQ, then you aught to redo the math done in this guide for your situation, I guarantee nothing for you :c._

### Fight-based Variance

Badge's value is significantly diminished if your guild uses the rogue Improved Expose talent and on lower armor bosses (E.G. Skeram).  Sixx's hunter sim has boss armor values for reference.  Since Improved Expose is not hugely pervasive and most bosses are not Skeram, I will eventually include math for fights with and without lower armor values.  <!-- TODO: exactly armor value where Badge is not worth using. -->

## Assumptions

- You're here for higher top end damage, not safer average DPS.
- You have Ashjre'thul.
- You have a 15% quiver.
- Haste effects should be stacked.
- FDing while a tinket is active is always DPS loss.
- The time variance of a successful swap (due to combat drop being inconsistent) doesn't matter since:
  1. You arn't currently using an active trinket
  2. It is unavoidable
- If you are max weaving:
  - You have Gril'leks, Ashkandi, or Barb.
  - Your weaves are consistently 2.6s or below.
- If you are normal waving:
  - You are not delaying your ranged rotation (~2.6s weaves)


## Rotation Timing

### Damage Scaling of Relevant Stats

At 25% crit, 6% melee hit, 9% ranged hit, 1900 rAP, 1700 AP (roughly T2):
| | dmg/AP | dmg/Crit |
|-|-|-|
| Auto | .34 | 9.96 |
| Multi | .33 | 12.52 |
| Aimed | .29 | 17.32 |
| Raptor | .33 | 9.18 |
| Melee | .18 | 7.71 |

These exact numbers aren't important since they vary with stats and gear, but their relationship to each other stays constant.  Notably, the rAP scaling of Multi becomes even stronger with T1 and the Barrage talent.  This shows us that our AP trinkets are best for Autos and Multis, whereas crit trinkets benefit our Aimed Shot the most.

### Rotation Time Tables

Below is a timetable explaining the max weave rotation.  We'll use these tables to estimate what actions will fall within the duration of a trinket depending on when it is used. 

| Time | Action | Time Spent |
|-|-|-|
| 0 | Run to ranged | 1.3
| 1.3 | Auto | 0.435 |
| 1.735 | Aimed Shot | 3.043 |
| 4.778 | Auto | 0.435 |
| 5.213 | Run to melee | 1.3 |
| 6.513 | Raptor Strike | 0 |
| 6.513 | Run to ranged | 1.3 |
| 7.813 | Auto | 0.435 |
| 8.248 | Multishot | 0.435 |
| 8.683 | Run to melee | 1.3 |
| 9.983 | Wait for melee swing | 0.03
| 10.013 | Melee | 0 |
| 10.013 | Wait for MS CD | 0.422 | 
| 10.435 | | |

In an effort to simplify the table, we'll reduce time spend running and waiting for cooldowns to a "Delay" column.  You can read the first row in the following table from left to right like, _"At time 0, we will Auto after 1.3 seconds (either moving or waiting for a CD), and it will take 0.435 seconds to cast."_  You'll notice that in the max weave rotation, we have to wait an odd 0.422 seconds at the end.  This is because a weaver with 2.6s weaves will actually complete the rotation fast enough that Multishot will not be ready the next time.  If you've been weaving and felt like you were waiting for multi, or catching up to it, then you're pushing the limits of max weaving.

### Max Weave Time Table

| Time | Action | Delay | Cast |
|-|-|-|-|
| 0 | Auto | 1.3 | 0.435 |
| 1.735 | Aimed Shot | | 3.043 |
| 4.778 | Auto | | 0.435 |
| 5.213 | Raptor Strike | 1.3 | |
| 6.513 | Auto | 1.3 | 0.435 |
| 8.248 | Multishot | | 0.435
| 8.683 | Melee | 1.330 |
| 10.013 | Repeat | 0.422 | 
| 10.435 |  |  | 

### Ranged Rotation Time Table

| Time | Action | Delay | Cast |
|-|-|-|-|
0 | Auto | 0 | 0.435
0.435 | Aimed Shot | 0 | 3.043
3.478 | Auto | | 0.435
3.913 | Multishot | | 0.435
4.348 | Auto | 2.087 | 0.435
6.870 | Auto | 2.522 | 0.435
9.826 | Aimed Shot | 0 | 3.043
12.870 | Auto | | 0.435
13.304 | Auto | 2.522 | 0.435
16.261 | Multishot | | 0.435
16.696 | Auto | 2.087 | 0.435
19.217 | Aimed Shot | | 3.043
22.261 | Auto | | 0.435
22.696 | Auto | 2.522 | 0.435
25.652 | Repeat | 2.522 | 
28.174 |  |  | 


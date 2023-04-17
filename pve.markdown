---
title: Talents, Rotation, Trinket Swapping (oh my)
---


Trueshot Aura is king.  If you're in a raid which does not currently have TS in every physical group then you should spec 31 marksman for it.  Hunters do not gain enough DPS from any other talent spec to justify not giving 100 AP to you and your 4 party members.
<!-- If you were not previously aware, this might be the first indicator that hunters are really not a core damage class in classic-- we are a ranged support class which kites and tranqs ;). -->

The default spec is [17/31/3](https://classic.wowhead.com/talent-calc/hunter/53000200502-05251030513051-3) where slaying applies.  Moving into AQ, all bosses are uncategorized so drop the 3 points in Survival for 3 more points in Ferocity. Points can be moved away from Improved Hunter's Mark if someone else in your raid has it.

You should seek 9% hit from armor/scope first-- but if you absolutely cannot get the hit from items (e.g. are very early in a season) then you can talent down SV into Surefooted.  **I have not confirmed this but colloquial advice is you should only deviate from the normal [17/31/3](https://classic.wowhead.com/talent-calc/hunter/53000200502-05251030513051-3) build to go Surefooted if you have less than 40% pet uptime on bosses.**

5/31/15 and 0/31/20 are popular PvP/PvE viable specs.  You'll take a small PvE damage hit for lots of really fun talents.  Improved Aspect of the Hawk is a fairly strong DPS buff (even in PvP) so only drop this if you really want to lean into PvP.

At that point, you could just respec and go Scatter Shot / LR spec though so /shrug.

### Misc Notes on SV talents

- Entrapment is extremely strong for group PvP like BGs since at 5/5 it has a 25% chance to snare enemies in Frost Traps _every tick and **does not DR.**_  It can cause some weird aggro issues when mobs with 0 threat are pulled through, though.
- Savage Strikes is mandatory for melee weaving in raids and helps make quick work of anyone in melee range.  
- Improved Wing Clip is almost always a worse choice than entrapment.
- Clever Traps synergizes strongly with Entrapment.
- Survivalist is slept on; 10% max health -after- buffs and consumes is very cozy.
- Deterrence is an incredible PvP cooldown for 1 talent point.  Be careful casting this when duelling a warrior.
- 1 point in Trap Mastery maxes its usefulness in PvP.
- The best part of Surefooted is the CC resist chance.
- Improved FD is good for [Dire Maul Tribute](#Dire-Maul-Tribute) runs and avoiding FD resists on bosses if you are performing active trinket [openers](#Openers).  Do not take this if you are not doing either of those.



# Rotations

With even crit RNG, hunters do around half of their damage from Auto Shot.  Their rotation, then, is about weaving in Aimed Shot and Multishot with minimally disrupting their Autos.

You should start with `Auto - aimed - auto - multi -...` and then cast aimed and multi off cooldown whenever it will not disrupt your autos*.  After 3 cycles both Aimed and Multishot wil come off cooldown at the same time: **always prioritize aimed.**  If you `mutli - auto - aimed -...` their CDs will stay synchronized and you will be delaying your Aimed Shot every time for a damage loss.

* see clipping:

### Clipping

The math used to calculate Aimed Shot's damage mostly ignores weapon speed and so two different weapons with the same DPS but different attack speeds will do very similar Aimed Shot damage.  However, the faster weapon will do less damage for each auto.  Because of this, we prioritize Aimed Shots over Auto Shots for weapons with an attack speed less than 3.  This means that you should cast Aimed Shot on CD even if it means interrupting a partially cast Auto Shot: this is called clipping.

Clipping fast attack speed weapons yields a DPS boost but will drain mana faster.  See [Ranged Weapons](#ranged-weapons) for specifics of whether you should clip a given weapon. 

### Openers

If your normal rotation is now just muscle memory and you happen upon some trinkets, its time to consider openers.  If you only have [Devilsaur Eye](https://classic.wowhead.com/item=19991/devilsaur-eye), then use it with Rapid Fire _before_ your first Aimed Shot and then go about your rotation normally.

#### Renataki's and Devilsaur Eye

The optimal opening for [Renataki's Charm of Beasts](https://classic.wowhead.com/item=19953/renatakis-charm-of-beasts), [Devilsaur Eye](https://classic.wowhead.com/item=19991/devilsaur-eye), and Rapid Fire is as follows:

![Renataki's Opener Timeline](media/rena_openner.png)

`Auto - DE and Aimed - rotation until Aimed is off CD - RF and Aimed - rotation until Aimed is off CD - Aimed - use Renataki's - FD and swap to passive trinkets - Aimed - Multi - Auto - into rotation.`

Using DE puts Renataki's on a 20s CD.  We delay using Rapid Fire so that it hastes 3 Aimed Shot (from the Rena reset). There is a 3 second timer after FD in which you cannot Auto Shot.  Because of this, if you FD and cast Aimed Shot after it and the Aimed Shot is hasted, you should cast Multishot immediately following it since you still won't be able to Auto.

*[This information, along with a useful macro, comes from Skinnay.](https://gist.github.com/skinnay-dev/0ce6448cc5f9e74336a096eb60708a99)*

## Trinket Swapping

**WELCOME GAMER, two forewords**

Don't worry about this if you're not going whole fights without clipping or DPS downtime. Trinket swapping is a very marginal DPS increase _but it is fun as fuck._

Feign Death has a 17% resist chance on mobs 3 levels above you.  It has a 4% chance to resist on mobs your level.  Spells always have a 1% resist chance.  This is why hunters will often run 3% spell hit to lower their resist chance against 60s in Diremaul North to that 1%.  However, it is never a DPS gain to wear spellhit or take Improved Feign Death against a boss; even at 17% chance, FD resists are a very minor DPS loss against bosses and that loss is outweighed significantly by the DPS gain of successful swaps.  If a single mob in combat with you resists, you will be unable to swap.  This means that you will have far more swap fails on fights with many adds.  Additionally, some fights like Patchwerk have environmental hazards (the slimes down the hall) that are technically mobs that can resist your Feign making swapping incredibly frustrating.  Use your best judgement but if it helps-- I swapped every fight of classic except for Patchwerk because the DPS loss of a resist is really just very small.

You will want to get a Feign Resist WA so that you can recover from a resist and resume DPSing as fast as possible (TODO add link here). 

If you only have a single swap (e.g. Devilsaur to passive trinkets) then simply mash a macro like this:

```
#showtooltip Feign Death
/stopattack
/petpassive
/cast Feign Death
/equip Royal Seal
```

If you have multiple swaps you'd like to do, carry on reading about the most cursed WA I've even had a hand in writing.

### Sillac's Autoswap 2: Electric Boukaloo

[https://wago.io/nWC_RLfn0]()

This WA is a permanent beta.  Its been through a whole 2 phases of classic so its pretty tried and true at this point but we make 0 guarantees about anything.

#### Background

Itemrack allows you to queue trinkets to swap on the next combat drop.  Swapping via the Blizzard Addon API incurs a ~400 MS delay for some fucking reason.  In addition to that, the combat drop event is almost always delayed and so stock Itemrack swaps ~800-1000 MS slower than it should.

An itemrack fix I wrote triggered the Blizzard API swap earlier, on the first frame that your inventory loses its combatlock (when the UNIT_AURA event corresponding to gaining FD is fired).  This sped swaps up by around ~200-400 MS by eliminating the combat drop delay but the swap delay still remained.

A macro which uses /equipslot can theoretically be mashed to trigger the frame that combat drops. This incurs neither the combat drop delay nor the swap delay but these macro's are a pain since you need to bake a new one (or modifiers for one) for each trinket (/combination of trinket) you would like to swap.

Sillac and I did a ton of troubleshooting and we wrote a WA to read Itemrack's queues to figure out the next swap and prep those items into specific inventory slots.   You mash a macro which FDs, and then attempts to equip the items in those slots via /equipslot 13 3 17 (which does not incur the swap delay).  When your trinket slots change the WA replaces the keybind to the macro you mashed with an Aimed Shot macro so that as you mash it--as soon as the swap goes off--you Aimed Shot.  When you press that aimed shot macro the WA swaps the keybind back to the FD swap for next time.

The end use case is that you setup Itemrack queues (or manually queue items in combat), enter combat, use your trinket(s), and then just mash your keybind.  If you do not resist then mashing the keybind will cause you to cast Aimed the moment you first can.  You carry on the fight, using more trinkets if you like, and repeating swaps until your itemrack queues are configured to stop, the fight ends, or itemrack begins repeating trinkets as they come off CD.

#### Setup

_**If you skip any steps, I'm not helping you.**_

1. Install itemrack (not my fix, just default version) and setup item queues according to how you want to rotate through your trinkets.  

2. Create the following macro named `Feign Swap`:
```
#showtooltip Feign Death
/petpassive
/use Renataki's Charm of Beasts
/script WeakAuras.ScanEvents("PREP_SWAP")
/cast Feign Death
/equipslot 13 <B> <S-1>
/equipslot 14 <B> <S>
```
**Replace `<B>` with the bag slot of your last normal (non-quiver) bag.  If your quiver is in your forth bag slot, then use 3.  Replace `<S>` with the number of slots in that bag and `<S-1>` with the number of slots in that bag - 1.**
For example, if you have an 18 slot bag in your 3rd slot and your quiver in your forth slot, then the last two lines of that macro would be:
```
/equipslot 13 3 17
/equipslot 14 3 18
```
3. Create the following macro named `Swap Aimed`:
```
#showtooltip Aimed Shot
/script WeakAuras.ScanEvents("SWAP_COMPLETE")
/cast Aimed Shot
```
4. Add the following line to the beginning of any macro you use Feign Death in but do not want to swap items: `/script WeakAuras.ScanEvents("UNPREP_SWAP")`.  Do not use a macro-less FD binding.

_4a. if you wish to use different macro names then you can, just configure them in the WA custom settings._ 

5. Make sure none of your trinkets are in your backpack.  They all need to be in bags.  They do not need to be in any specific bag, but swapping to any trinkets in your backpack will incur a sizable delay.  Make sure you have at least 2 empty slots in your last bag.

6. Place the `Feign Swap` macro onto your bars and bind it to whatever keybind you want to mash to swap and follow up with aimed.  _Do not bind `Swap Aimed`, do not slot `Feign Swap` into multiple action slots._

7. _Install and pray?_

#### HELP!?

If you have any issues please post in the trinket-juggling channel of the [Classic WoW Hunter Discord](https://discord.gg/8TVHxRr).  Please do not @ me, I read every message in that channel.

### Swapping Armor

Is swapping your trinkets not enough for you?  Me neither.  Get all of t2.5 and then wear it into every fight RF is up, use RF, do your openner, then FD swap with this macro back to t3 to always get 2m RF reduction: 

```
/stopattack
/petpassive
/use Renataki's Charm of Beasts
/cast Feign Death
/equip Cryptstalker H
/equip Cryptstalker S
/equip Cryptstalker T
/equip Cryptstalker L
/equip Cryptstalker B
/equip Band of R
/equip Mark
```

You can also wear your T3 into Sapph with a Greater Frost Protection Potion pre-popped for your DPS cooldowns and then feign into frost resist gear.  _Your healers will -love- you for this._

Swapping into Rocket Helm for KT add phase is actually very helpful for CCing a fourth add while your team burns KT down.

#### Advanced Advanced Math Section

There is a weird flowchart about whether you should actually Aimed Shot out of your FD swaps.  _The optimization here is in the order of fractions of DPS over even incredibly short fights._  This is basically an esoteric optimization for people consistently 100 parsing.  But I like math and optimizing and esoteric things so I'm putting this here and its my guide so you can't stop me c:

_**Should I aimed or auto out of FD?**_

- If you weave or are using Ren's, aimed shot out of FD.
- If you are doing a ranged rotation, auto out of FD when unhasted.
- If you are doing a ranged rotation, you are hasted, and MS CD is up, aimed and clip your next auto with MS (`FD, aimed, ms, auto`). 
- If you are doing a ranged rotation, you are hasted, and MS is on CD, I honestly have no idea.


Considering only the ranged rotation where you have gaps in between your autos: the mechanics of FD are that if you FD, a timer starts = to the length of an unhasted autoshot with your current weapon (- .5s for cast time).  If at any point you autoshot and do nothing else while laying in FD, then you will cast an auto as soon as that timer is up (1 unhasted auto after you STARTED FD).

If you do anything else out of FD (move or cast a non-auto) the timer is reset.

So if you FD and then auto, you delay your rotation by the difference between an unhasted and a hasted auto (3.4 - 2.9 = .5 for Xbow).  If you FD and then aimed you delay your rotation by-- the time it takes between casting FD and combat drop + trinket swap + the difference between an unhasted auto and aimed shot (~.3 + .5).  Its tricky though-- because this depends on your rotation and when you want to FD.


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



For each trinket, and trinket pair
for each rotation
with varying amounts of haste
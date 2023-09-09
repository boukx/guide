---
title: Talents, Rotation, Trinket Swapping (oh my)
---


Trueshot Aura is king.  If you're in a raid which does not currently have TS in every physical group then you should spec 31 marksman for it.  Hunters do not gain enough DPS from any other talent spec to justify not giving 100 AP to you and your 4 party members.
<!-- If you were not previously aware, this might be the first indicator that hunters are really not a core damage class in classic-- we are a ranged support class which kites and tranqs ;). -->

[](https://www.wowhead.com/classic/talent-calc/embed/hunter/53000200502-05251030513051-3)

The default spec is [17/31/3](https://classic.wowhead.com/talent-calc/hunter/53000200502-05251030513051-3) where slaying applies.  In AQ, all bosses are uncategorized so drop the 3 points in Survival for 3 more points in Ferocity. Points can be moved away from Improved Hunter's Mark if someone else in your raid has it.

You should seek 9% hit from armor/scope first-- but if you absolutely cannot get the hit from items (e.g. are very early in a season) then you can talent down SV into Surefooted.  **Colloquial advice is you should only deviate from the normal [17/31/3](https://classic.wowhead.com/talent-calc/hunter/53000200502-05251030513051-3) build to go Surefooted if you have less than 40% pet uptime on bosses.**

5/31/15 and 0/31/20 are popular PvP/PvE viable specs.  You'll take a small PvE damage hit for lots of really fun talents.  Improved Aspect of the Hawk is a fairly strong DPS buff (even in PvP) so only drop this if you really want to lean into PvP.

### Misc Notes on SV talents

- Entrapment is extremely strong for group PvP like BGs since at 5/5 it has a 25% chance to snare enemies in Frost Traps _every tick and **does not DR.**_  It can cause some weird aggro issues when mobs with 0 threat are pulled through E.G. before the C4 door in DMT.
- Savage Strikes is mandatory for melee weaving in raids and helps make quick work of anyone in melee range.  
- Improved Wing Clip is almost always a worse choice than Entrapment.
- Clever Traps synergizes strongly with Entrapment.
- Survivalist is slept on; 10% max health -after- buffs and consumes is very cozy.
- Deterrence is an incredible PvP cooldown for 1 talent point.  Be careful casting this when duelling a warrior.
- 1 point in Trap Mastery caps its usefulness against players for PvP.
- The best part of Surefooted is the CC resist chance.
- Improved FD is good for [Dire Maul Tribute](#Dire-Maul-Tribute) runs and avoiding FD resists on bosses if you are performing active trinket [openers](#Openers).  Do not take this if you are not doing either of those.



# Rotations

With even crit RNG, hunters do around half of their damage from Auto Shot.  Their rotation, then, is about weaving in Aimed Shot and Multishot with minimally disrupting their Autos.

You should start with `Auto - aimed - auto - multi -...` and then cast aimed and multi off cooldown whenever it will not disrupt your autos[(* see clipping).](#-clipping)  After 3 cycles both Aimed and Multishot will come off cooldown at the same time: **always prioritize aimed.**  If you `multi - auto - aimed -...` their CDs will stay synchronized and you will be delaying your Aimed Shot every time for a damage loss.



### * Clipping

The math used to calculate Aimed Shot's damage mostly ignores weapon speed and so two different weapons with the same DPS but different attack speeds will do very similar Aimed Shot damage.  However, the faster weapon will do less damage for each auto and will have its autos delayed more by Aimed Shots long cast time.  Because of this, we prioritize Aimed Shots over Auto Shots for weapons with an attack speed less than 3.  This means that you should cast Aimed Shot on CD even if it means interrupting a partially cast Auto Shot: this is called clipping. Clipping fast attack speed weapons yields a DPS boost but will drain mana faster; if you're running out of mana of fights while clipping and consuming correctly, you should revert to not clipping regardless of your weapon speed.

### Openers

If your normal rotation is now just muscle memory and you happen upon some trinkets, its time to consider openers.  If you only have [Devilsaur Eye](https://classic.wowhead.com/item=19991/devilsaur-eye), then use it with Rapid Fire _before_ your first Aimed Shot and then go about your rotation normally.

#### Renataki's and Devilsaur Eye

The optimal opening for [Renataki's Charm of Beasts](https://classic.wowhead.com/item=19953/renatakis-charm-of-beasts), [Devilsaur Eye](https://classic.wowhead.com/item=19991/devilsaur-eye), and Rapid Fire is as follows:

![Renataki's Opener Timeline](media/rena_openner.png)

`Auto - DE and Aimed - rotation until Aimed is off CD - RF and Aimed - rotation until Aimed is off CD - Aimed - use Renataki's - FD and swap to passive trinkets - Aimed - Multi - Auto - into rotation.`

Using DE puts Renataki's on a 20s CD.  We delay using Rapid Fire so that it hastes 3 Aimed Shot (from the Rena reset). There is a 3 second timer after FD in which you cannot Auto Shot.  Because of this, if you FD and cast Aimed Shot after it and the Aimed Shot is hasted, you should cast Multishot immediately following it since you still won't be able to Auto.

*[This information, along with a useful macro, comes from Skinnay.](https://gist.github.com/skinnay-dev/0ce6448cc5f9e74336a096eb60708a99)*

## Melee Weaving

Melee weaving is a small DPS gain for skilled hunters; **you will likely lose dps for your first dozen or so hours melee weaving** so please, practice on DMT ogre spirits for a while before trying it in raid.  Done well, melee weaving with optimal weapons sacrifices 0 ranged damage for an occasional Raptor Strike.  

### Static Weaving

Static weaving is the act of meleeing a target close to you between autos on a target far away from you.  It is made extremely simple via the Mouseover Raptor Strike/Melee [macro.]({{ site.baseurl }}#macros)  Simply hold your cursor over a nearby target and hit the macro between ranged shots.

### "Normal" Weaving

Normal weaving is the basic single-target weaving rotation wherein you run to the target and Raptor Strike between autos when both your Aimed Shot and Multi-Shot are on CD.  With Zanza of Swiftness, it takes a good hunter ~2.5s round trip which is lower than most strong weapon's attack speed: thus you won't delay your Auto Shot weaving correctly.  Note--**you should never weave while hasted from Rapid Fire or Improved Aspect of the Hawk.**

### Max Weaving

Max weaving is the most melee heavy weave rotation and the only one which genuinely sacrifices ranged damage for melee damage.  It should only be performed when consistently weaving sub 2.5 seconds.  The rotation is `auto - aimed - auto - raptor - auto - multi - melee ...` repeat.  Max weaving is a DPS loss over normal weaving and sometimes the ranged rotation when your melee or ranged weapons are too fast.  **Do not max weave while hasted.**

## Trinket Swapping

A foreword: don't worry about trinket swapping if you're not going whole fights without clipping or DPS downtime. Trinket swapping is a very marginal DPS increase and its incredibly hard to justify taking loot to potentially lose DPS due to unskilled play.

Feign Death has a 17% resist chance on mobs 3 levels above you.  It has a 4% chance to resist on mobs your level.  Spells always have a 1% resist chance.  This is why hunters will often run 3% spell hit to lower their resist chance against 60s in Diremaul North to that 1%.  However, it is never a DPS gain to wear spellhit or take Improved Feign Death against a boss; even at 17% chance, FD resists are a very minor DPS loss against bosses when reacted to quickly and that loss is outweighed significantly by the DPS gain of successful swaps.  If a single mob in combat with you resists, you will be unable to swap.  This means that you will have far more swap fails on fights with many adds.  Additionally, some fights like Patchwerk have environmental hazards (the slimes down the hall) that are technically mobs that can resist your Feign making swapping incredibly frustrating.  Use your best judgement but if it helps-- I swapped every fight of classic except for Patchwerk because the DPS loss of a resist is really just very small.  You should get a Feign Resist WA so that you can recover from a resist and resume DPSing as fast as possible. 

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


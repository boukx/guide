# Hunters: A ~~Supplementary Guide~~ Compendium

This started as an eclectic collection of notes I made in phase 2 classic for newer hunters. With Season of Mastery starting soon, I'm filling out the gaps to hopefully make a smoother journey for new hunters.

Vanilla hunter is a broken, cursed monstrosity of bad design and poor planning; it's nearly my favorite MMO class ever.  I hope this guide gives you the information on its quirks and bugs needed to enjoy the class for its weirdness.  

As always, if you have any questions please ask in the [Classic WoW Hunter Discord](https://discord.gg/8TVHxRr).


## Table of Contents
- [Addons, Weakauras, and Macros](#addons-weakauras-and-macros)
  - [Macros](#macros) 
  - [Weakauras](#weakauras)
  - [Trinket Swapping](#trinket-swapping)
- [Talents](#talents)
  - [Raid Viable PvP Talents](#raid-viable-pvp-talents)
- [Rotations](#rotations)
  - [Clipping](#clipping)
  - [Openers](#openers)
- [Buffs](#buffs)
- [Pets](#pets)
- [Gear](#gear)
  - [T2](#t2)
  - [Ranged Weapons](#ranged-weapons)
- Farming
  - [Dire Maul Tribute](#dire-maul-tribute)

# Addons, Weakauras, and Macros

Outside of Azeroth my work leans heavily on designing software to enable analysts to make good descisions; I change my UI very often from PvE optimized Elv setups to retro game RP themes to most recently a minimalist, Blizz-like PvP UI.

**You should use addons to compliment how you want to play the game.** Copying another person's UI that doesn't play like you isn't going to make you a better player; fixing little issues with your UI can remove friction that you would experience for hours and hours.  Below I'm going to list a healthy mix of addons but if you're just getting into things, then install Leatrix, Weakauras, Questie, DBM, and start your adventure.  c:

### General Purpose Addons
- **Leatrix Plus** enables a bunch of things like faster auto loot, further camer distance, auto invites, moving/scaling buffs and frames.  All of which by default are off, so you can pick and choose the features you need via /ltp or the minimap button.  I highly recommend installing this and then browsing the settings from time to time.
- **Weakauras** (2?) is basically mandatory.  Weakaura's are mini-addons that can be shared in game.  I'll be recommending a couple specific to hunter further down.
- **Questie** helps you quest.

### Actionbars

- If you're interested in **ElvUI**, install that before any more addons in this guide as it includes nameplates and unitframes and a whole host of UI bits and pieces.  It can take a bit to initially set it up but the strength of Elv is being able to maintain a consistent style over nearly all of your UI elements by setting borders, fonts, colors, and having them applied to all UI elements.  I'm a very big fan of Elv for more serious raiding.
- **Dominos** or **Bartender** are actionbar addons (that just do actionbars).  They have all the same features so pick either, I use Dominos.
- The vanilla actionbars are totally usable.  Binding keys can be a bit of a pain but don't let anyone bully you into using an actionbar addon if you like the vanilla look.

### PvE
- **DBM** and **BigWigs** give you vital information about boss encounters.  Like the actionbar addons, they do all the same things and they even work with eachother at this point.  Install one. I've used both. I use DBM currently because it has a better PvP plugin for AB flags.
- **Details** is a meter addon.  You can see healing, interrupts, damage taken, and all sorts of things.
- **ThreatClassic2** is a threat addon.  Details has TinyThreat included but TC2 has all sorts of nice features like de-normalizing threat on range or warnings when your threat gets over a certain % or value or both.
- I use default raid frames scaled down with MoveAnything.  If you have a healer alt probably get a raid frame addon.
- **HealBarsClassic** (formerly known as HealComms) shows incoming healing on nameplates and raid frames.  I highly recommend installing it even as a DPS and then setting it to only show healing on you and your pet; knowing a heal is incoming can let you make better decisions in raids and PvP.

### Gameplay (sorta PvPish)

This section is about addons which help you optimize your gameplay a bit more.  Because vanilla WoW doesn't really have hard PvE content, most of these are far more useful in PvP so you can skip them if you're not planning to engage with that side of things at all.

- Get a nameplates addon if you're not using Elv.  I used to use **KUI** because I installed it once and liked it (good defaults).  Now I use Plater, lots of people love **ThreatPlates**.
- **BigDebuffs** replaces your character in your unitframe with the icon and duration of any CC or powerful cooldown thats currently active.  Its a great additional piece of information and can be configured to show exactly the level of detail you want.  **LoseControl** is similar.
- **ClassicAuraDurations** adds aura durations to auras on allies and enemies.  Use this to time chain CC on PvP targets or even just keep a mob CC'd over a long pull.
- I always forget why I have **OmniCC** installed but when I uninstall it I feel empty inside.
- **Itemrack** lets you manage whole equipment sets and make UI elements for quickly swapping gear.  Its really useful for trinket swapping as a hunter and for managing PvP items like rocket helm and boots.  TrinketMenu does most of what people use Itemrack for in PvP if you prefer that.  
- I could write a whole section on how garbage most peoples use of scrolling battle text addons is but I'll try and be succinct.  I use **MiksScrollingBattleText** to show combat drops and items/spells comming off CD.  It even makes a little sound!  If you install MSBT, please, please filter it aggressively so 50% of your screen isn't useless damage numbers.  Begrudgingly, if those numbers give you dopamine-- _then scale them to 36 font size and send me your PvP montages._
- **OPie** is a radial menu, good for: pet spells you use infrequently; tracking spells; consumes, etc.

### PvP

- I like **Diminish** for PvE even (when it works), but it shines in all PvP giving you timers for your target's DR. 
- **OmniCD** shows player, target, and party CDs in an easier way.  I use it for Brez and DI in PvE and a whole lot of things in PvP.
- **RatBG Battleground Target Frames** is arena frames for a BG.
- **UnitScan** and **Spy Classic** are borderline broken for finding and targetting slippery targets/rares.

### Hunter Specific

- **A swing timer** shows the time until your next auto shot.  There are a couple popular ones pinned in the hunter discord but some arn't working properly.  Mine works if you want: [https://wago.io/YcGbmuPhy]()
- **A range indicator** shows the approximate distance between you and your target. There are a number of these in the hunter discord.  They all work.
- [Raikho's Weave Helpers exist.](https://wago.io/p/Raikho)

### Economy and Skills

- **TradeSkillMaster** or TSM is great if you play the game to bulk auction.  It requires setup and only really helps bulk posting for flipping/merching.  If you don't get excited about a 20s margin on enchanting mats, probably don't use TSM.
- **Auctioneer** is my lightweight AH addon of choice.  There are a bunch others that work well, I've just used this one.
- **Gathermate2** and the Wowhead datapack for it are great for gatherers.

### Misc
- I feel bad putting **Masque** in this category because I'm sure some people will miss it but its such a simple quality of life improvement.  Classic icons are inconsistent and have different borders on them.  Masque with its default Classic skin fixes this; **BlizzBuffsFacade** applies the fix to your buffs as well.  You can get fun and skin your icons all weird if you want but just installing these 2 addons cleans up your UI with 0 effort.
- **Leatrix Maps** is great.  I use it so my map isn't fullscreen and so I can see unexplored areas that I'd otherwise be checking a wiki page for from time to time.
- **eAlign** shows a grid on your screen for aligning UI elements when you type /align.
- **MoveAnything** lets you move and scale anything.  Its buggy and out of date but its really nice for minor tweaks.

## Macros

If you have read other classic addon guides you may have heard of a required Aimed Shot macro for avoiding the retry timer; this was fixed late in classic and remains fixed in Season of Mastery.  You can use Aimed Shot in macros if you'd like, but you do not need a macro to just cast Aimed Shot, you can use the spell from your spell book with no issues.

Spammable, target finding auto shot macro:
```
#showtooltip
/cleartarget [dead]
/targetenemy [noharm]
/stopattack
/cast !Auto Shot
```

Spammable, target finding auto shot with petattack and dash/dive:
```
#showtooltip
/cleartarget [dead]
/targetenemy [noharm]
/cast !Auto Shot
/stopattack
/petattack
/cast [pet:Cat,harm]Dash; [pet:Owl,harm]Dive
```
I'd bind both and use them situationally.  Not having a keybind to attack without pet will hurt you down the line. 

Not a macro, but **bind petpassive to an easily accessible key.**  Its the seal icon on your pet bar and hitting it even while the pet is already in that setting calls it back to you or its petstay spot.  You will regret not having this the first, second, and third time you pet is sprinting towards a raid boss before anyone is ready.

Reasonable pet care macro which will Call/Revive/Mend pet without any modifiers.
```
#showtooltip
/use [@pet,nodead,exists] Mend Pet
/stopmacro [@pet,nodead,exists]
/use [@pet,dead,exists] Revive Pet
/castsequence reset=2 Call Pet, Revive Pet
```

Binding your Aspect of the Cheetah like this allows you to hit it again to cancel.  Using spellbook Cheetah doesn't let you cancel during your GCD.  You should do the same with Aspect of the Pack.
```
#showtooltip
/cancelaura Aspect of the Cheetah
/cancelaura Aspect of the Pack
/cast Aspect of the Cheetah
```

I bind all my other aspects like `/cast !Aspect of the Hawk` so that mashing them doesn't disable them.

Eagle Eye chaining macro lets you recast Eagle Eye from your current spot:
```
#showtooltip
/cleartarget
/cast !Eagle Eye
```

Eat/Drink/Prowl/Shadowmeld:
```
#showtooltip
/use Alterac Manna Biscuit
/use Conjured Crystal Water
/use Morning Glory Dew
/use [mod:shift] Conjured Cinnamon Roll
/use [mod:shift] Roasted Quail
/cast [mod:alt] !Shadowmeld
/cast [mod:alt] !Prowl
```

Adding flag dropping into your mount macro is good if you do any PvP
```
#showtooltip Swift Green Gryphon
/cancelaura Horde Flag
/cast Reins of the Swift Mistsaber
```

Use top trinket and RF (add Berseking if Troll):
```
#showtooltip Rapid Fire
/use Rapid Fire
/use 13
```

Using items (rocket boots, parachute cloak, etc)  Replace X with 1 for helm, 8 for boots, 13 for trinket 1, 14 for trinket 2, 15 for cloak, 16 for main hand weapon:
```
#showtooltip
/use X
```

### Mouseover

Sorta a mouseover, this fires Flare at your cursor: `/cast [@cursor] Flare`

What people bind as mouseover macros is pretty subjective.  I'm going to list all of mine in order of most popular to sorta niche things to mouseover.  I always use the syntax `[@mouseover,harm,nodead][]` which will use the mouseover target if it is hostile and not dead, otherwise cast at your target; remove `[]` if you don't want that fallback condition.

Highly recommend mouseover Scatter Shot
```
#showtooltip Scatter Shot
/stopattack
/petpassive
/cast  [@mouseover,harm,nodead][] Scatter Shot
```

I put Naxx totem stopping into my mouseover HM but I'm not sure whether this will work in SoM
```
#showtooltip Hunter's Mark
/cleartarget
/targetexact Lightning Totem
/targetlasttarget [noexists]
/cast [@mouseover,harm][] Hunter's Mark
```

Mouseover Raptor Strike/Melee is very useful for lots of free DPS.  This is also weave friendly if you do not queue the attack while out of melee:
```
#showtooltip Raptor Strike/cleartarget
/targetlasttarget
/targetenemy [noharm]
/tar [@mouseover,harm]
/use Raptor Strike
/use Mongoose Bite
/startattack
/stopmacro [@mouseover,noharm]
/targetlasttarget
/use !Auto Shot
/targetlasttarget [noexists][dead]
```

Mouseover stings are useful for mana drain, DoTing rogues, and blanketting a DoT if you need to trap

- `/cast [@mouseover,harm,nodead][] Viper Sting`
- `/cast [@mouseover,harm,nodead][] Serpent Sting`
- `/cast [@mouseover,harm,nodead][] Scorpid Sting`

Petattack mouseover is good to send pet to a target while you ranged another: `/petattack [@mouseover,harm,nodead]`

I include Raptor in a mouseover Wing Clip macro because I almost always want more damage on a WC target.
```
#showtooltip Wing Clip
/stopcasting
/cleartarget [dead][help]
/cast Raptor Strike
/cast [@mouseover,harm,nodead][] Wing Clip
/startattack
```

### Feign Death

Below is [an advanced section for trinket swapping](#trinket-swapping)-- if you're not interested and just want an FD macro use the following one.  Some people will add `/cast Freezing Trap` afterwards so they can mash a single key to FD and trap.  I don't like this, but you do you.

```
#showtooltip Feign Death
/stopattack
/petpassive
/cast Feign Death [combat]
```

### Weakauras

This is an unorganize list of Weakauras I like or use:
- [Smarnz's Improved Range Check](https://wago.io/-EGVBCgFU) shows your range to a target.
- [Stokbaek's Castbar for Multi/Aimed with Pushback](
https://wago.io/92y4H96_t) is a castbar with estimated pushback.  Hunters should have at least one castbar/shot timer; this one is nice.
- Optional, but [this WA](https://wago.io/oYIjS228K) shows your shot delays so that you can tighten your rotation.
- [Weaving Timer Collection](https://wago.io/oBjregGjL) shows the timings of all components of your weave.
- [Predictive Weave Bar](https://wago.io/K6nl2clmn) is insane.
- [Tranq Shot Tracker](https://wago.io/GaRv7KK51/1) tracks tranq shots.
- [Instance History](https://wago.io/OXlZupyKm/6) for tracking your instance lockouts.
<!-- https://wago.io/FX0Q1REGv -->


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

You can also wear your T3 into with a Greater Frost Protection Potion pre-popped for your DPS cooldowns and then feign into frost resist gear.  _Your healers will -love- you for this._

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

# Talents

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

You should start with `Auto - aimed - auto - multi -...` and then cast aimed and multi off cooldown with an auto between them.  After 3 cycles both Aimed and Multishot wil come off cooldown at the same time: **always prioritize aimed.**  If you `mutli - auto - aimed -...` their CDs will stay synchronized and you will be delaying your Aimed Shot every time for a damage loss.

### Clipping

The math used to calculate Aimed Shot's damage mostly ignores weapon speed and so two different weapons with the same DPS but different attack speeds will do very similar Aimed Shot damage.  However, the faster weapon will do less damage for each auto.  Because of this, we prioritize Aimed Shots over Auto Shots for weapons with an attack speed less than 3.  This means that you should cast Aimed Shot on CD even if it means interrupting a partially cast Auto Shot: this is called clipping.

Clipping fast attack speed weapons yields a DPS boost but will drain mana faster.  See [Ranged Weapons](#ranged-weapons) for specifics of whether you should clip a given weapon. 

### Openers

If your normal rotation is now just muscle memory and you happen upon some trinkets, its time to consider openers.  If you only have [Devilsaur Eye](https://classic.wowhead.com/item=19991/devilsaur-eye), then use it with Rapid Fire _before_ your first Aimed Shot and then go about your rotation normally.

#### Renataki's and Devilsaur Eye

The optimal opening for [Renataki's Charm of Beasts](https://classic.wowhead.com/item=19953/renatakis-charm-of-beasts), [Devilsaur Eye](https://classic.wowhead.com/item=19991/devilsaur-eye), and Rapid Fire is as follows:

![Renataki's Opener Timeline](rena_openner.png)

`Auto - DE and Aimed - rotation until Aimed is off CD - RF and Aimed - rotation until Aimed is off CD - Aimed - use Renataki's - FD and swap to passive trinkets - Aimed - Multi - Auto - into rotation.`

Using DE puts Renataki's on a 20s CD.  We delay using Rapid Fire so that it hastes 3 Aimed Shot (from the Rena reset). There is a 3 second timer after FD in which you cannot Auto Shot.  Because of this, if you FD and cast Aimed Shot after it and the Aimed Shot is hasted, you should cast Multishot immediately following it since you still won't be able to Auto.

*[This information, along with a useful macro, comes from Skinnay.](https://gist.github.com/skinnay-dev/0ce6448cc5f9e74336a096eb60708a99)*

# WIP beyond this point, some infos outdated

# Buffs

Hunters get the short end of the buff stick.  Dire Maul Tribute's [Fengus' Ferocity](https://classic.wowhead.com/spell=22817/fengus-ferocity) is only melee AP.  Battle Chicken's [squak](https://classic.wowhead.com/spell=23060/battle-squawk) is only melee attack speed.  These buffs are only useful if you are melee weaving.  Hell, even the AP component of [Rallying Cry of the Dragonslayer](https://classic.wowhead.com/spell=22888/rallying-cry-of-the-dragonslayer) is only melee (luckily the crit does affect ranged attacks).

### Consumables
<!-- agi scroll, juju power, juj might -->
There are many guides for hunter consumes so I'm not going to recreate them here.  Just note: there are consumes for your ranged attacks, consumes for buffing your pet (yes, it makes a significant DPS increase), and consumes for melee weaving.

If nothing else, try to have [Elixir of the Mongoose](https://classic.wowhead.com/item=13452/elixir-of-the-mongoose) and [Grilled Squid](https://classic.wowhead.com/item=13928/grilled-squid) with you at all times.  [Greater Fire Protection Potion](https://classic.wowhead.com/item=13457/greater-fire-protection-potion) are key to protecting your Aimed Shot from suffering pushback on Firemaw, Vael, etc.


# Pets

Pets can do a considerable percentage of a hunter's damage even if they are not Beast Mastery hunters.  All hunters should focus on keeping their pet alive (pet uptime).  Hunters raiding BWL and MC should take the following pet skills to maximize damage: max fire resist, max shadow resist, max dash, max claw, rest in stamina.

# Gear

[Simming](https://docs.google.com/spreadsheets/d/1BIlB2P1kyV_QdD4ULQzvZvS6hK6BDouUQkyHQzCvBGI/edit?usp=sharing) is the only way to answer the question of "should I wear X or Y?"  Gear guides can tell you what to pursue, but simming is the end all for making the best of what you have.  For ally hunters, Skinnay already has a [list of simmed gear sets](https://gist.github.com/skinnay-dev/39f71f3cce1c64b95142f7e0e0d97bca).

Its notable that stat priorities change depending on your faction and rotation.  Alliance members will favor stats like Agi which are increased by kings and weavers will take notably worse weapons for ranged DPS so that their raptor strikes hit harder.

### T2

The T2 8 piece set bonus debuff has a proc rate of .5 ppm.  It takes up a debuff slot per proc; [if multiple procs overlap, it takes up multiple debuff slots.](https://classic.warcraftlogs.com/reports/zw8FcCnL19qxjhmR#hostility=1&type=auras&spells=debuffs&ability=23577&source=100&fight=last) though this doesn't matter in SoM. Each hunter wearing T2 in a raid slightly increases every other hunters DPS.

### Ranged Weapons

Hunter's ranged weapons are poorly described by tooltips.  DPS numbers are often misleading as slower weapons will do much better damage than faster ones.  Below is a list of hunter weapons tiered by their DPS for a tier 2 MM hunter and whether the weapons should be clipped.  Please be informed-- it is not worth taking a Striker's Mark or something similar from a melee when a blue dungeon weapon is better.

| Weapon | AS | Best DPS | Worst DPS | Auto DPS |
|--------|--------------|----------|-----------|----------|
| Nerubian Slavemaker | 3.2 | 599, Full |  503, Clipped | 304 (1st) |
| Ashjre’thul | 3.4 | 571, Full | 491, Clipped | 283 (9th) |
| Larvae of the Great Worm | 3.0 | 558, Clipped | 530, Full | 290 (3rd) |
| Soulstring | 2.9 | 551, Clipped | 534, Full | 293 (2nd) |
| Crossbow of Imminent Doom | 3.1 | 547, Clipped | 507, Full | 276 (13th) |
| Rank 14 Weapons | 2.9 | 538, Clipped | 521, Full | 285 (8th) |
| Rhok’delar | 2.9 | 534, Clipped | 517, Full | 282 (10th) |
| Fahrad’s Reloading Repeater | 3.2 | 530, Full | 447, Clipped | 261 (22nd) |
| Bloodseeker | 3.3 | 528, Full | 451, Clipped | 259 (23th) |
| Huhuran’s Stinger | 2.7 | 525, Full | 517, Clipped | 286 (6th) |
| Blessed Qiraji Musket | 2.6 | 525, Full | 506, Clipped | 286 (6th) |
| Carapace Spine Crossbow | 3.3 | 523, Full | 447, Clipped | 257 (26th) |
| Dragonbreath Hand Cannon | 2.8 | 521, Clipped | 516, Full | 281 (11th) |
| Heartstriker | 2.6 | 516, Full | 498, Clipped | 280 (12th) |
| Flawless Arcanite Rifle | 3.0 | 510, Clipped | 482, Full | 233 (28th) |
| Striker’s Mark | 2.5 | 509, Full | 480, Clipped | 274 (14th) |
| Gurubashi Dwarf Destroyer | 2.8 | 508, Clipped | 503, Full | 272 (16th) |
| Blastershot Launcher | 2.6 | 508, Full | 491, Clipped | 274 (14th) |
| Toxin Injector | 2.0 | 503, Clipped | 498, Full | 290 (3rd) |
| Core Marksman Rifle | 2.5 | 503, Full | 474, Clipped | 270 (18th) |
| Mandokir’s Sting | 2.6 | 502, Full | 484, Clipped | 270 (18th) |
| Hoodoo Hunting Bow | 2.8 | 499, Clipped | 493, Full | 265 (20th) |
| Stoneshatter | 2.9 | 499, Clipped | 482, Full | 258 (25th) |
| Silithid Husked Launcher | 2.8 | 496, Clipped | 490, Full | 263 (21st) |
| Bow of Taut Sinew | 2.2 | 496, Full | 445, Clipped | 272 (16th) |
| Grand Marshal’s Bullseye / High Warlord’s Recurve | 1.8 | 494, Full | 470, Clipped | 287 (5th) |
| Ancient Bone Bow | 2.8 | 490, Clipped | 484, Full | 259 (23rd) |
| Gryphonwing Longbow | 2.7 | 477, Full | 473, Clipped | 254 (27th) |

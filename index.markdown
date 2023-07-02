Hunters in vanilla are incredible levelers, capable of soloing a wide variety of content, and have by far some of the most intricate vanilla systems in pet taming and management; the class is fairly easy to pick up with a few stumbling blocks but has a very high capacity for skill expression in the open world, instances, and PvP.

In a raid setting, Hunter is a great perspective to lead with a relatively simple ranged rotation and the ability to control the pace of trash via pulling.  Without large balance changes, it remains a sort of ranged support class; you contest warriors and rogues on some loot and do not contest an equally skilled one in damage.  If you want to top meters, hunter isn't a particularly good class to play, but, every raid will want 1-3 for pulling and tranqing -and- good pulling hunters will dramatically increase your raids speed and quality of life.

As always, if you have any questions please ask in the [Classic WoW Hunter Discord](https://discord.gg/8TVHxRr).

# Faction, Race, Profession

On horde, troll hunters dominate with their Berserking racial while orcs are slightly behind in PvE.  In PvP, orc stun resist can make or break fights.  For the Alliance, night elfs and dwarves racials are equally weak in PvE, though provide different situational advantages in PvP; dwarves can Stoneform off rogue's Blinds and night elfs can use Shadowmeld to eat/drink/lurk in the open world.  For PvE, pick either, for organized PvP/duels, pick dwarf, for open world shenanigans, pick nelf.

All ~~hunters~~ _classes_ are advised to go Engineering as one of their professions in vanilla.  Its simply too good to turn down.  If you plan on farming Dire Maul Tribute runs, your other profession should be enchanting but there is no need to level it in vanilla to be able to disenchant.  No other profession dramatically impacts hunter performance in vanilla.

# Macros

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

## Mouseover

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
#showtooltip Raptor Strike
/cleartarget
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

## Feign Death

```
#showtooltip Feign Death
/stopattack
/petpassive
/cast Feign Death [combat]
```

Some people will add `/cast Freezing Trap` afterwards so they can mash a single key to FD and trap.  I don't like this, but you do you.  More advanced FD macros are included in the [PvE section for trinket swapping.]({{ site.baseurl }}/pve#trinket-swapping)  

# Weakauras

This is an unorganized list of Weakauras I like or use:
- [Smarnz's Improved Range Check](https://wago.io/-EGVBCgFU) shows your range to a target.
- [Stokbaek's Castbar for Multi/Aimed with Pushback](
https://wago.io/92y4H96_t) is a castbar with estimated pushback.  Hunters should have at least one castbar/shot timer; this one is nice.
- Optional, but [this WA](https://wago.io/oYIjS228K) shows your shot delays so that you can tighten your rotation.
- [Weaving Timer Collection](https://wago.io/oBjregGjL) shows the timings of all components of your weave.
- [Predictive Weave Bar](https://wago.io/K6nl2clmn) is insane.
- [Tranq Shot Tracker](https://wago.io/GaRv7KK51/1) tracks tranq shots.
- [Instance History](https://wago.io/OXlZupyKm/6) for tracking your instance lockouts.
<!-- https://wago.io/FX0Q1REGv -->


# Addons

**You should use addons to compliment how you want to play the game.** Copying another person's UI that doesn't play like you isn't going to make you a better player; fixing little issues with your UI can remove friction that you would experience for hours and hours.  Below I'm going to list a healthy mix of addons but if you're just getting into things, then install Leatrix, Weakauras, Questie, DBM, and start your adventure.

### General Purpose Addons
- **Leatrix Plus** enables a bunch of things like faster auto loot, further camer distance, auto invites, moving/scaling buffs and frames.  All of which by default are off, so you can pick and choose the features you need via /ltp or the minimap button.  I highly recommend installing this and then browsing the settings from time to time.
- **Weakauras** allows you to install are mini-addons/UI elements that can be shared in game.  I'll be recommending a couple specific to hunter further down.
- **Questie** helps you quest.

### Actionbars

- If you're interested in **ElvUI**, install that before any more addons in this guide as it includes nameplates and unitframes and a whole host of UI bits and pieces.  It can take a bit to initially set it up but the strength of Elv is being able to maintain a consistent style over nearly all of your UI elements by setting borders, fonts, colors, and having them applied to all UI elements.  I'm a very big fan of Elv for more serious raiding.
- **Dominos** or **Bartender** are actionbar addons (that just do actionbars).  They have all the same features so pick either, I use Dominos.
- The vanilla actionbars are totally usable.  Binding keys can be a bit of a pain but don't let anyone bully you into using an actionbar addon.

### PvE
- **DBM** and **BigWigs** give you vital information about boss encounters.  Like the actionbar addons, they do all the same things and they even work with eachother at this point.  Install one. I've used both. I use both currently because BW has better customization and DBM has a better PvP plugin for AB flags.
- **ThreatClassic2** is a threat addon.  Details has TinyThreat included but TC2 has several nice features like normalizing threat on range or warnings when your threat gets over a certain % or value or both.
- **Details** is a meter addon.  You can see healing, interrupts, damage taken, and all sorts of things.
- **LibHealComm-4.0** shows incoming healing on nameplates and raid frames.  I highly recommend installing it even as a DPS and then setting it to only show healing on you and your pet; knowing a heal is incoming can let you make better decisions in raids and PvP.

### Gameplay (sorta PvPish)

This section is about addons which help you optimize your gameplay a bit more.  Because vanilla WoW doesn't really have hard PvE content, most of these are far more useful in PvP so you can skip them if you're not planning to engage with that side of things at all.

- Get a nameplates addon if you're not using Elv.  I use **Plater** since its very easy to add modules to; I've used **KUI** in the past because its plug and play.  Lots of people love **ThreatPlates**.
- **BigDebuffs** replaces your character in your unitframe with the icon and duration of any CC or powerful cooldown thats currently active.  Its a great additional piece of information and can be configured to show exactly the level of detail you want.  **LoseControl** is similar.
- **ClassicAuraDurations** adds aura durations to auras on allies and enemies.  Use this to time chain CC on PvP targets or even just keep a mob CC'd over a long pull.
- I always forget why I have **OmniCC** installed but when I uninstall it I feel empty inside.
- **Itemrack** lets you manage whole equipment sets and make UI elements for quickly swapping gear.  Its really useful for trinket swapping as a hunter and for managing PvP items like rocket helm and boots.  **TrinketMenu** does most of what people use Itemrack for in PvP if you prefer that.  
- I could write a whole section on how garbage most peoples use of scrolling battle text addons is but I'll try and be succinct.  I use **MiksScrollingBattleText** to show combat drops and items/spells comming off CD.  It even makes a little sound!  If you install MSBT, please, please filter it aggressively so 50% of your screen isn't useless damage numbers.  Begrudgingly, if those numbers give you dopamine-- _then scale them to 36 font size and send me your PvP montages._
- **OPie** is a radial menu, good for: pet spells you use infrequently; tracking spells; consumes, etc.

### PvP

- I like **Diminish** for PvE even (when it works), but it shines in all PvP giving you timers for your target's DR. 
- **OmniCD** shows player, target, and party CDs in an easier way.  I use it for Brez and DI in PvE and a whole lot of things in PvP.
- **RatBG Battleground Target Frames** is arena frames for a BG.
- **UnitScan** and **Spy Classic** are borderline broken for finding and targetting slippery targets/rares.

### Hunter Specific

- **A swing timer** shows the time until your next auto shot.  There are a couple popular ones pinned in the hunter discord but some arn't working properly for Era right now.  I currently use **WeaponSwingTimer SixxFix.**
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
- **MoveAnything** lets you move, scale, and/or hide all UI elements.  Its buggy and out of date but its really nice for minor tweaks.

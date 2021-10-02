# Star Wars Mayhem 3
To download, click Code -> Download ZIP.


We need Mayhem veterans to help with balancing. Just play the game and provide feedback!

Keep in mind that pacing is supposed to be much different from Mayhem 3. So please read the Beta Guidelines below before posting about issues. Many 'imbalances' between factions are actually intended!


## Features:
* Star Wars factions, ships, stations, and wares
* factions now very different from each other
* new events & plot decisions
* own customizable t-file (9973-L044)

## Mayhem newcomer friendly !!!:
- tutorials revised
- much weaker bad guys (Xenon, OCV)
- inverse difficulty scaling. Mayhem 3 had a challenging start and grindy endgame. SWM3 starts very easy and you can finish the main plot with only a medium sized empire. And after that new things can happen
- removed all time sensitive difficulty scaling

## Factions:
* Argon - Empire / Remnant
* Boron - New Republic
* Goner - N/A
* Kha'ak - Sith
* OCV - Sith
* Paranid - CIS
* Split - Rebellion
* Teladi - Republic / Old Republic / Jedi
* Xenon - Sith
* Yaki - Mandalorian / Pirates

## Installation:
1. Download and install Litcube's Universe
    * http://litcube.xtimelines.net/wiki/index.php/Main_Page

2. Download and install Mayhem 3
    * https://www.moddb.com/mods/mayhem/downloads/mayhem-3-main

3. Download and install the Mayhem 3 Graphics Pack
    * https://www.moddb.com/mods/mayhem/downloads/mayhem-3-graphics2

4. Download and install the Mayhem 3 Sound Pack
    * https://www.moddb.com/mods/mayhem/downloads/mayhem-3-ambient-soundtrack

5. Download and install the Star Wars Data Pack
    * https://drive.google.com/file/d/1-DQHxfKdEYsp99IL1_Bf4suZeCPKwyEo/view?usp=sharing

6. Optional: Download and install the Backgrounds Pack
    * https://forum.egosoft.com/viewtopic.php?p=4997068#p4997068

7. Optional: Download and install temetvince's Mod
    * https://forum.egosoft.com/viewtopic.php?f=94&t=441824&sid=afdedee043647f8001edf81c29e3c677

8. Copy the files found with this README to your game installation directory.

## General Changes:
* most ships have much fewer different weapon choices (bit like in M3R, but often less extreme). This was necessary to stop NPCs from using bad guns
* there is usually only 1 good loadout per ship and all the crappy rest got removed. Ion weapons are only available to player, pirates, Sith and mercs
* Laser energy is basically irrelevant (also like in M3R). This helps to balance OOS battles
* no laser knockback effects. This improves capships a lot during in-sector battles against fighters

### Includes some M3R features:
* preinstalled video goggles (but for Transporter you need the upcoming SWM3R submod)
* AI claims unknown sectors unrestricted if the player owns more than 15 sectors
* toDo: faster repairs + hacking UI helpers

### Custom Mayhem Settings:
SWM3 also makes changes to Mayhem 3's standart t-file. These options are supposed to prevent certain extreme outcomes during your playthrough. Most of them are recommended for SWM3, but you can also replace the file and use your preferred custom Mayhem 3 settings if you like.

* general invasion protection threshold below which small factions get ignored and no longer invaded by others increased from 3 to 5 sectors (certain SWM3 features have unique exceptions to this rule)
* slower pirate respawns > delay is 50% longer
* NPC fleets retreat slightly earlier to try and limit their combat losses > original power comparison threshold was 4, is now slightly more sensitive at 3
* unlocking the final plot stage only requires to terraform 3 planets instead of 10 and there is an alternate trigger (20 player sectors)
* no higher research costs for random ship types
* disabled Mayhem's coalition system
* additional waits in the capship turret script (this doesn't hurt at all and performance is supposedly better)
* no NPC factions builds only half size squadrons when they own few sectors (SWM3 has NPC production discounts)
* AI ships which are waiting very long to be outfitted but can't due to a lack of resources get their weapons for free after just 1h instead of having to wait 4h

# Beta Guidelines:
## Differences to Mayhem 3:
* factions start very slow and escalate from early to middle to lategame
* each phase got special rules, different fleet compositions and uses different ship types
* the 3 phases are separated by 2 milestones that the player must achieve: owning 4 sectors and completion of the terraforming quest or owning 20 sectors
* no time sensitive progress or difficulty scaling (Xenon)
* faction phases are loosely based on iconic SW lore or certain themes from the movies or expanded universe
* OCV waves are MUCH easier. Supposed to already start at the end of your mid-game. The true endgame is supposed to be a megawar between the Empire and the New Republic

!!! Certain key developments are supposed to happen roughly similar in almost every playthrough! SW factions are asymetric !!!

For example the Galactic Empire is always meant to be more powerful than the Rebel Alliance. But their sectors frequently turn against them with a new mechanic. The Empire does have strong fleets, but they are supposed to waste a lot of time conquering all this lost territory back. Making the Empire feel more like a defensive faction with internal problems. And the Rebels are more like a guerilla group who actually switch their base locations during the playthrough.

## This is why we need testing:
Everything below is still mostly just theory. With how it's designed it should already work, but certain things likely need adjustment. Please report if your factions develop vastly different from how its described here. So that we can  put additional safeties in. We are able to do a lot in terms of balancing, like tweaking special abilities or invasion protections, provide production buffs or nerfs and  also change fleet compositions to be different in each phase and for each faction.

* all the way down you can find faction dossiers. They describe how factions are supposed to be balanced in a perfect version 1.0
* 'Lore Summary' quickly describes which iconic SW theme each phase of this faction is based on
* 'Quirks' lists all special rules, restrictions or abilities
* 'Strategic Evaluation' describes how the faction should develop and behave in 90% of cases

## Feedback we are interested in:
* do factions really develop the way they are supposed to?
* do the phases change properly? Are new ship types getting built? Here you find an overview, when and how new ships unlock + all dynamic fleet compositions https://docs.google.com/spreadsheets/d/1NPQHVd0JuL-ihS8eoQotkDhuUva8TzNj-j3q4EZQ2Hs/edit?usp=sharing
* does any faction have major resource shortages at certain plot stages?
* serious performance issues with large NPC fleets? (looking at you CIS and Empire)
* any inappropriate worker ships in use by NPCs? (too slow, too little cargospace, or seemingly too fragile against pirates)
* any ship prices to change? (keep in mind that for the player there already is a population regrowth mechanic to prevent that he just spams super cheap ships)
* certain ships too powerful? We generally want to stick close to SWLU balance as much as possible and not change ship stats too much. If something seems overpowered we prefer to make it more expensive and reduce the amount that the NPCs are using.
* NPC weapon loadouts are ok?
* are NPC outpost specialization levels properly updated in all outposts? (can be checked with a debug option in your player console) This is how outposts should develop during phase 1/2/3: Empire: 50/60/80 Rebels: 65/70/80 New Republic: 50/60/90 CIS: 50/60/80 Republic: 50/70/80  Mandalorians: -/70/80
* missing text updates

# The typical SWM3 playthrough:

## Galaxy Creation:
* unfortunately you always need to select Republic as a major faction and Rebels as minor faction
* i've contacted Joubarbe so that we can properly hook into the galaxy generator and make this obsolete. But for now this is the only way we got.
* due to how SWM3 is balanced the Empire faction always needs the Rebels in the same game or they might be too powerful too quickly

## Phase 1:
* to prevent that factions blob out of control immediately after gamestart (like they often do in M3) this first phase runs with several handbrakes activated
* attack fleets are weaker than defense fleets
* Sith (Xenon) don't scale up over time. They have weaker ships and should generally never take over the galaxy unless the player goes well into and beyond phase 2
* at this stage the Republic is supposed to loose hard. But if that happens too quickly their special negotiation ability will magically protect them against any more invasions so that they are still able to fire up their Clone Wars tech in phase 2
* how quickly does the Republic loose sectors in your game, and to whom?
* Rebel Alliance and New Republic should also be very weak and not conquer new sectors at all (apart from unknown sectors)
* New Republic should really just loose sectors until they are small and get invasion protected (this should happen somewhere in phase 1 or 2)
* Rebels will occasionally gain new sectors with their special Rebel Cell ability. These new sectors should often spawn in Empire territory. Is this actually true or do we need to focus that even more on the Empire? Do you think new Rebel sectors appear too often or not frequently enough? On average the Rebels should never ever own more than 16-20 sectors (unless you help them)
* at first the Empire should mostly fight border skirmishes, but without actually conquering anything major. Their battlegroups should be fairly slow and weak. But their defense is supposed to be super tough and they should basically almost never loose a sector other than having it defect to the Rebels. After 1-2 days they should almost exclusively be very busy with reclaiming territory they lost to Rebels.
* How fast does the CIS expand? I think their fighter swarms might deal high damage and also quickly cover ground between factory kills, which could speed up their invasions too much. But of all factions they also got the most fragile ships and often loose many of them. Does their resource consumption need to get toned down or are they still building ships just fine?

phase 2 should happen after roughly 2-3 days (with average playstyle)

## Phase 2:
* Mandalorian faction arrives with full strength battlegroups which are more powerful than the strongest currently existing defender fleets and much more powerful than any other currently existing battlegroups
* up to the beginning of phase 2 the Sith (Xenon) should not have taken over more than a few sectors at most.
* Mandalorians should now be able to conquer sectors almost unchallenged for roughly 1 day or so

1-2 days later

* most factions should now have significantly ramped up their fleet size with new ship types
* especially average battlegroup strength should have more than doubled compared to gamestart. Sector conquest messages should start to pop up way more often now.
* in phase 2 the Republic is supposed to massively build up its fleets from almost nothing and is generally supposed to become a very successful faction (Clone Wars)
* Mandalorians should never be able to grow much bigger than 15-20 sectors until the other factions have also become strong enough to stop them
* how are the Rebels doing? Any MonCal Cruisers roaming through the galaxy yet? Do they still keep the Empire busy enough so that it doesn't invade other factions too much?

phase 2 should last roughly 2-4 days. The player can trigger phase 3 either by terraforming 3 planets or by getting a large empire with 20 or more sectors

## Phase 3:
* how is the New Republic doing? (supposed to be mostly dead with only 4-5 sectors but i fear the Sith might sometimes wipe them out)
* have the Sith ever accomplished anything yet? (should not be much at all)

Sith invade entire galaxy (previously OCV)
* are larger factions generally able to handle those Sith invasions on their own, or do the Sith completely take over?
* it's supposed that the Sith can never wipe out the New Republic or the Empire

After the special 'Katana Fleet' event for the New Republic gets implemented in a future version:
* does the New Republic use their new fleet to start conquering sectors and generally make a comeback?
* how long does it take until the NR can be considered a 'major' faction?
* is the Empire still in fighting shape to be the main antagonist for the New Republic? (the NR should generally win this in the very long run but it should be the biggest conflict yet)
* could the CIS also still last a bit? (preferred)
* the Republic is supposed to fall behind like in the early game and mostly get conquered by others
* when the New Republic has grown to a certain size the Rebels loose their sector turning ability. That allows the Empire to focus on the NR because they don't need to chase after lost sectors all the time

# Faction Dossiers:

## Galactic Empire:

Lore Summary:
Phase 1: early Empire days up to Episode IV (basic Star Destroyer 1, basic TIEs and carrier tactics)
Phase 2: Episode VI tech and beyond, advanced light/medium ships
Phase 3: adds a few next-gen SDs from the sequel movies

Abilities:
* Sector Groups: good defense fleets
* Rebel Hunt: special permission to completely wipe the Rebel Alliance out: (actually a disadvantage) 

Strategic evaluation:
* rarely looses battles. High chance to reach endgame in good shape
* greater risk to get targeted by the Rebel Cell ability
* doesn't expand very well and wastes lots of time  reconquering rebel sectors
* starts with slow, iconic Imperial class 1 Star Destroyers, using mostly carrier tactics and basic TIE fighter swarms
* later unlocks many new ship types like Strike cruisers, Lancer frigates and advanced fighters like the TIE Defender. Late capitals focus more on firepower. Also unlocks more medium fleets which can travel faster on the galaxy map.
* large endgame fleets with many advanced capitals

## Rebel Alliance:

Lore Summary:
Phase 1: early Rebellion days, old tech and no MonCala cruisers
Phase 2: Episode VI
Phase 3: 

Abilities:
* Underdogs: weak fleets, especially at gamestart
* Sympathy: builds ships cheaper due to secret funding and donations
* Safe Havens: Rebel faction can be larger than usual to still be ignored by other factions and protected against their invasions
* Always on the Run: Rebel sectors never protected against the Empire.
* Rebel Cells: special ability which causes random NPC sectors to join them! Doesn't work against small factions and Empire sectors are always more likely to turn than others. Multiple sectors can turn at once when the Rebel faction is small. A large rebel faction looses this ability.
* HyperJump specialists: Rebel outpost stations work like jump beacons! Instant teleport across their territory.
* Deep Strikers: naturally invades distant targets way behind the territory border, invasions can also last longer

Strategic evaluation:
* starts with small territory and bad economy, but is gifted with significant early production discounts
* almost never grows large and powerful without player help but is difficult to wipe out
* unstable. Looses many sectors but also gains new ones in entirely different locations
* when the faction is small it doesn't get invaded and naturally develops 'safe havens' (with the Rebel Cell ability). But these sectors never last long when close to the Galactic Empire
* scattered and isolated
* squadrons jump across the galaxy and over hostile territory
* invades unpredictable and everywhere
* starts the game without any large capitals but later builds MonCalamari cruisers in limited numbers

## New Republic:

Lore Summary:
Phase 1: problematic founding period. Lack of ship crews, low numbers. (exaggerated theme of the Thrawn book trilogy)
Phase 2: same as 1 but unlocks advanced post-Endor capitals
Phase 3: removes all problems, boosts faction and enables potential for galaxy wide expansion (theme: New Republic total dominance until beginning of Yuzan Vongh conflict). Also adds a few resistance ships from the sequel movies

Quirks:
* Tech Victory: can field the most powerful fleets, but first needs to survive into the lategame
* Crew Shortage: low numbers across all squadrons. Only fixed in lategame.
* Turtle Focus: decent rearguard defense squadrons
* Katana Fleet: special lategame event grants a super powerful battlegroup to help them grow into a powerful endgame faction

Strategic evaluation:
* advanced ships, but expensive and limited numbers
* faction usually looses hard until becoming a minor faction which is simply ignored by other NPC empires.
* should flip the table with free Katana fleet during endgame. But these are just lots of old Dreadnought cruisers which are not too powerful and should slowly die out.
* potential to grow into a monster faction with insane economy boost and many advanced post-Endor capships. Terrible foe if they ever own the galaxy.
* player can wipe them out easily in phase 2

## Separatist CIS:

Fleet Lore Summary:
Phase 1: before Clone Wars (Episode 1) mostly just Droid fighter swarm galore
Phase 2: early-mid Clone Wars (Episode 2+)
Phase 3: late Clone Wars (Episode 3)

Quirks:
* Rigid Swarmer Tactics: heavy focus on cheap droid fighters. Later they adapt but never fully give up this fleet doctrine

Strategic evaluation:
* underestimated damage potential
* fragile ships, frequent losses
* some squadrons only consist of Droid fighters which can travel very fast

## Republic:

Lore Summary:
Phase 1: Old Republic up to Episode 1 (Era of Peace theme)
Phase 2: Clone Wars
Phase 3:

Quirks:
* Rusaan Reformation: bad early military
* System Autonomy: large starting territory
* Negotiations: the Republic faction can be much larger and still be ignored by other factions and be protected against their invasions. But this ability gets lost when the early game ends.
* The Clone Wars: midgame unlocks unique production discounts due to public war support. Massive militarized buildup with new ship types. Transition takes  a while

Strategic evaluation:
* easy prey during early game. Ancient ships from the Old Republic and in limited numbers. Only some inner core defense fleets are quite strong and got larger capitals.
* usually looses many sectors in the first days of your playthrough. But the Negotiation ability ensures that they reach the midgame still somewhat capable.
* Clone Wars unlock Venator carrier tactics with heavy fighters and lots of supporting frigates, but they never like to use many M6 or M2.
* faction might grow large on its own some time after reaching the Clone Wars era, but if initial losses were too much to handle they also might need your help.
* this faction starts with a huge economic advantage  and gets buffed greatly during the midgame. But if you want to support them you should really use that middle stage of your playthrough. Because lategame they'll fall behind again.

## Mandalorians:

Lore Summary:
Phase 1: 
Phase 2: Mandalorian Wars theme
Phase 3: 

Quirks:
* Late Arrivals: this faction doesn't doesn't own any sectors at gamestart. At first they only exist in the form of an underground terrorist organization.
* Mandalorian Uprising: a real Mandalorian empire gets created in a special event. You get 3 major choices how to react to this (see below).
* Shady Buisness: not targeted by pirates and mandalorian outposts double down as pirate bases!
* Deep Strikers: naturally invades distant targets way behind the territory border, invasions can also last longer
* A new Mandalore: gifted with more efficient production from having an inspiring leader. Advantage over other factions gets lost in the lategame

Strategic evaluation:
* hostile against all factions except the player
* passively hurts surrounding economy with pirate spawns
* aggressive start. Mandos arrive with strong invasion fleets and rush a rather unprepared gameworld. After 1-2 days the other navies will have catched up and the mandalorian offensive is likely getting stuck.

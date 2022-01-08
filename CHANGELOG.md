Task Tracking for v1.0.0
https://github.com/temetvince/swm3/projects/1

2022/01/08 -Hector
- Quick-Trade added
- external trade limit default 200k for player
- strict import disabled on default

2022/01/03 -temetvince
- All ships returned to their original Angular Acceleration values
- Class rotation variables have been increased by these amounts:
    - M3 = 40%
    - M4 = 25%

2022/01/02 -temetvince
- All ships now have Angular Acceleration set to 50
- Class rotation variables have been increased by these amounts:
    - M1/M2/TL = 200%
    - M7 = 50%
    - M6 = 25%
    s- TM/TP/TS = 10%

2021/12/26 -Hector
- fixed green corp sometimes trading in Energy + Waste (rare but unintended, new games only)

2021/12/25 -Hector
- savegame compatibility
- changes to the fighter flanking maneuver
- increased minimum required distance to the enemy
- less aggressive flanking positions (doesn't overshoot the enemy as often)
- flanking position is now speed dependent
- fast fighters fly much further around the enemy before attacking. Slow fighters stick much closer to their fleet.
- enabled flanking also for carrier support fighters
- fleets will not send their fastest ships ahead to attack military targets which are further away than 40km. (this makes NPC fleets very deadly because they stick in tight formation until right before the battle) Does not apply when attacking civilian targets (stations, satellites and freighters)
- player fleets now completely ignore enemy satellites and freighters
- added 2 new targeting priorities: 'Freighters' and 'Stationary Ships' (satellites) Use these settings on separate fleets if you want to hunt down such targets
- added Transporter Device as default equipment on all ships (there were still way too many issues with unresponsive ships 'waiting for docking clearance'. this is dirty but fixes it like in M3R)
- Explorer Workers only load 5 satellites instead of 10
- increased general ship following distance

2021/12/23 -Hector
- lategame total war of Galactic Empire vs. New Republic (with t-file options)
- early game Katana search quest
- fighter rebalance
- slightly reduced Outpost natural population growth rate
- research station tutorial message
- encyclopedia fixes/revisions/additions
- fixed check for nearby enemies before docking. Now has a 20km minimum range (fleets with low scanning range didn't work well)
- fighters never use stationary tactics again (too much friendly fire when player enters sector)
- added 'State of the Galaxy' journal section (current special rules, gifted factions, etc.)
- increased default starting territory for Mandalorians from 5% to 8% of the galaxy
- Mandalorian Task Forces could spawn a vanilla Mammoth
- added Explorer Whitelist. Enables you to monitor enemy sectors and/or override the standart blacklist so it only affects other Workers
- fixed Lasertower using mining laser


2021/11/13 -Hector
- Mandalorian plot complete implementation
- Midgame Quickstart
- encyclopedia update
- M3R drydock restoration
- 5km scanning range
- faster capship repair
- M3R hacking UI helpers
- reduce Republic/Mando phase 3 production spec to 50% + smaller fleets
- buffed Republic phase 2 to 80%
- new blobbing prevention (NPC owning 40% of galaxy waits with more invasions until phase 3)
- M6/TM dynamic (slightly closer) engagement range against capships
- new fighter combat script (M2 acp version with added fallback and evasive flying)
- no fallback on M6/TM

2021/10/30 -Hector
- hyperlane quest (t-file optional)
- new t-file option player Jump Beacons only work between certain sectors
- vastly increased abandoned ships at gamestart (not claimable by NPC tugs). New game only
- added abandoned ship classes M4 + TP
- Ascension goals don't ask for very specific classes. Only for freighters or fighters in general.
- reduced long research grind to unlock alternate ship blueprints. 20% of your generated research points add to a global discount which reduces all future project costs (t-file customizable)
- fixed repair laser
- increased speed of all mining ships
- all fighter miner variants are now haulers.
- Star Wars-ialized vanilla naming in the outpost station construction UI
- Mandalorians got a TS Miner (Republic YV-100 clone)
- followers and escorts don't dock if enemies are nearby
- battlegroup squadron followers who are getting under fire while attacking stations now call their leader into the fight if he is still stuck attacking the station
- removed a restriction which prevented ships from counterattacking if they already had a target which is close (there are still many more restrictions other than that)
- battlegroups which only consist of fighters and which invade a sector will first try to clear a short range perimeter of all enemy fighters before doing anything else. This gets repeated if the current leader dies and a new one gets assigned. (overall better response of fighter battlegroups against new hostiles before going back to kill stations again)


2021/10/13 -Hector
- fight script overhaul (!fight.attack.object)
- fleetcommander can't be carrier for support ships (Mayhem.Support.FindCarrier)
- faster strafing (globals)
- tBullet speeds, sizes + little tweaks
- removed vanilla ships from generic missions
- spacesuit faster (tships) + SETA (warelist)
- typo in ministry of war
- player miners t-file option

2021/10/06 -Hector
- Republic more weak phase 1 defender squadrons
- GameCreator: Rebels sectors scatter and give 50% territory to Republic
- GameCreator: New Republic gives 15% territory to Empire
- M3 t-file: reverted NPC retreat threshold back to 4:1
- M3 t-file: maintenance cost and cycle doubled (cost remains the same but increase over time halved)
- increased Republic phase 1 invasion protection threshold from 12 to 18 sectors
- reduced maximum time till next Rebel Cell activation from 30h to 26h
- most Sith ships use weaker lasers
- greatly slowed down all Sith ships
- +50% delay between 'big' Sith invasions (with capships)
- very slow capship speed increased a bit
- pirate M6 spawn chance halved

2021/10/04 -Hector
- OOS damage fixed

2021/10/03 -Hector
- added optional backgrounds template file for galaxy generator
- fixed missing t-file descriptions
- added t-file option to hide spammy claim and protactorate expiration messages
- changed squadrons: more early activity due to less global border patrol ships and slightly better BGs, stronger Mando attack in phase 2, Rebels + Republic weaker allround, Empire stronger allround

2021/10/02 -temetvince
- Merge Hector's changes
- Incorporate Hector's Backgrounds Mod
- Modify Readme - new sw datapack

2021/10/02 - Hector
- ship weapon compatibility
- main plot flavor texts (should be almost complete now)
- some fixes
- TL cargospace divided by 34

2021/09/26 - Hector
- lasers balanced
- SW ship WareLists. Also added video goggles like in M3R
- removed all laser knockback effects
- Vulture Droid gets better 5 MJ shield
- removed 1 200MJ shield from TIE-Defender, B-Wing Adv. and TIE-Scimitar Miner (all 3 still op enough)
- all resource volumes divided by 2 , Ore/Silicon by 8
- Alliance job names
- Betty silenced for all job racenames


2021/09/25 - Hector#2
- included M3R lategame unknown sector spam fix
- allow Empire to wipe Rebels out
- weak empires cannot claim unknown sectors which are reserved for player
- Republic era 1 invasion prevention
- Rebel invasion prevention
- Rebel deep strike ability
- plot TL didn't have shields

2021/09/25 - Hector
- added Rebel Cell ability
- text fixes in conquer and truce scripts
- added a custom vanilla Mayhem 3 t-file with a few recommended settings
    - higher invasion protection threshold
    - slower pirate respawns
    - NPC fleets retreat slightly earlier to limit their combat losses
    - unlocking the final plot stage only requires to terraform 3 planets
    - no higher research costs for random ship types
    - disabled Mayhem's coalition system
    - additional waits in the capship turret script
    - no NPC factions builds only half size squadrons
    - reduced AI cheat wait time to get equipment for free

2021/09/25 - temetvince
- Reduced price of ships:
    - M5/M4/M3: divided by 4
    - M6/TM/TL/M8: divided by 5
    - TS/TP: divided by 8
    - M7/M1/M2: divided by 6
- Updated readme to remove install instructions for the rebalance mod

2021/09/24 - Hector
- NPC outpost production booster (for new stations and existing stations when new galaxy progress triggers)

2021/09/22 - Hector
- Rebels jump between outposts, t-file optional

2021/09/19 - Hector
- starter SW ships
- any text changes now in the new t-file
- bugfix laser races
- smaller M6 merc groups
- removed remaining Xenon ship types
- removed NPC terran ship construction
- removed all timers from empire size factor + Yaki plot trigger
- removed racename vocals by limiting duration of the sound to 1 ms in the index file (mov/00044.xml)

2021/09/15 - temetvince
- Fixed M1/M2 models not appearing in game
- Fixed wrong faction name being used for ships/jobs
- Added animated main menu
- All docks now use Star Wars models
- Faction ranks are now Star Wars based

2021/09/13 - Hector
- Galaxy Generator SW flavor (mayhem_data/dialog.xml and localization.xml)
- laser compendium races (Mayhem.GetLaser.Race)
- no random NPC terran Worker ships (Mayhem.GameCreator.Populate)
- no random NPC terran military ships (Mayhem.GameCreator.Populate.AddSquadrons)
- free plot TL is a Neutron Bulk Cruiser (Mayhem.Mission.PlotTL)
- generic Xenon combat mission spawns a Sith leader (Mayhem.Mission.SpawnXenons)
- generic Xenon combat mission follower are Sith (Mayhem.Mission.Create)
- new game Xenon defenders and non-respawning scout parties ship types are Sith. New game Khaak scout ship types are Sith, Khaak race changed to Sith (Mayhem.GameCreator.SpawnXenons)
- Xenon garrison units are Sith (Mayhem.GameCreator.SpawnXenons.PopStation)
- OCV ship types are Sith, OCV race and warning text changed to Sith (Mayhem.OCV.Generate)
- Kha'ak raid spawn Sith ship types, Kha'ak race and warning text changed to Sith (Mayhem.SpawnKhaakRaid)
- Interorbital storage delivery boy and escort are SW ships (Mayhem.SpawnDeliveryBoy)

2021/09/11 - temetvince
- Added all star wars ships
- Moved all vanilla ships to Neutral Race
- Modified all wares to be Star Wars based

Task Tracking for v1.0.0
https://github.com/temetvince/swm3/projects/1

2021/10/06 -Hector
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

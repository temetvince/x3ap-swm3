Task Tracking for v1.0.0
https://github.com/temetvince/swm3/projects/1

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

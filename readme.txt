Statistics Mod 0.3
==================

Statistics Mod records combat, magic, exploration, economy, and realm
statistics throughout the current Heroes of Might and Magic III map.
Hero records and player totals are stored in the savegame.

Requirements
------------
- ERA 3
- Era Erm Framework

Opening the statistics window
-----------------------------
Right-click the Quest Log button on the adventure map. Alternatively, hold
Shift and right-click an empty adventure-map tile.

Use the arrow buttons beside the hero name to browse all heroes owned by the
current player. Hover over headings, values, controls, and the hero portrait
for short explanations. Close the window with the checkmark or Esc.

Recorded statistics
-------------------
Combat:
- Fights, killed enemy creatures, and lost units
- Melee, ranged, and commander damage
- Highest physical hit
- Battle replays started with the hero

Magic:
- Hero spell damage, highest spell hit, and average spell damage
- Combat spells, adventure-map spells, and commander spells
- Spell points spent in combat
- ACM spell upgrades

Exploration:
- Land and sea travel
- Unique map objects and primary-stat objects visited
- Treasure chests, artifacts, and resource piles collected
- Towns and mines visited
- Chambers, Arenas, Raid Bosses, and Battle Commander victories

Realm & Player:
- Game day, active play time, and average turn duration
- Recorded gold income, expenses, and collected resources
- Player-wide fights, defeated enemy heroes, and spell totals
- Towns and mines captured
- Creatures recruited from town dwellings and external map dwellings, with
  WoG and HD Mod Buy All purchases included

Savegames and battle replays
----------------------------
Statistics belong to the current map session and remain available after
loading a savegame. Combat values are committed after battle. When a battle
is replayed, values from the discarded result are rolled back before the new
attempt is counted. The replay itself is recorded for the participating human
hero.

Optional integration
--------------------
Compatible counters are read from Advanced Classes Mod, Arena Mod, Raid Boss
Mod, and Battle Commander scripts when available.

Current limitations
-------------------
- Economy totals are derived from resource snapshots. Gains and expenses that
  occur between snapshots can partly cancel each other out.
- Scripted damage changes can occasionally differ from displayed game damage.

Version 0.3 is a testing release. Reports about incorrect or duplicated
counters are especially welcome.

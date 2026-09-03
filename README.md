# Statistics Mod

Statistics Mod records combat, magic, exploration, economy, and realm statistics throughout the current *Heroes of Might and Magic III* map. Hero records and player-wide totals are stored in the savegame and remain available after loading.

## Version 0.3

Version 0.3 introduces the four-panel **Session Statistics** window and substantially expands the first prototype.

### Combat

- completed fights;
- killed enemy creatures;
- melee, ranged, and commander damage;
- highest physical hit;
- units permanently lost in completed battles;
- battle replays started with the hero;

### Magic

- direct hero spell damage and highest spell hit;
- average damage per combat spell cast;
- combat and adventure-map spells;
- commander spells;
- spell points spent in combat;
- spell upgrades earned when Advanced Classes Mod is active.

### Exploration

- travelled land and sea tiles;
- unique map objects and primary-stat objects visited;
- treasure chests, artifacts, and resource piles collected;
- towns and mines visited;
- completed creature-bank chambers, Arenas, Raid Bosses, and Battle Commander encounters when the corresponding mods provide these values.

### Realm & Player

- current map day, active play time, and average turn duration;
- recorded gold income, gold expenses, and collected resources;
- player-wide fights and defeated enemy heroes;
- total spell activity and travelled distance;
- captured towns and mines;
- creatures recruited from town dwellings, including the WoG and HD Mod **Buy All** functions, and separately from external adventure-map dwellings.

## Opening the window

Right-click the **Quest Log** button on the adventure map to open the statistics window. Alternatively, hold **Shift** and right-click an empty adventure-map tile. Use the arrow buttons beside the hero name to browse all heroes owned by the current player. Hover over headings, values, controls, and the hero portrait for short explanations. Close the window with the checkmark or **Esc**.

## Savegames and battle replays

Statistics belong to the current map session and are stored in the savegame. Combat values are committed after battle. If a battle is replayed, values from the discarded result are rolled back before the new attempt is counted, while the replay itself is recorded for the participating human hero.

## Requirements

- ERA 3
- Era Erm Framework

## Optional integration

The mod reads compatible counters from Advanced Classes Mod, Arena Mod, Raid Boss Mod, and Battle Commander scripts when those mods are active.

## Current limitations

- Economy values are derived from resource snapshots. Multiple gains and expenses between two snapshots can partly cancel each other out.
- Scripted damage changes can occasionally differ from the displayed in-game damage.
- A few specialized damage sources outside normal armies, hero spells, and supported commanders are not tracked separately.

Version 0.3 is a testing release. Reports about incorrect or duplicated counters are especially welcome.

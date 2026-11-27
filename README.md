# Unique Drops Forever (BETA)

A World of Warcraft Forever addon for browsing NPC loot, finding item sources, and tracking your own drops. The database works offline during play.

## Install

1. Download the addon ZIP from the [v0.36.0 beta release](https://github.com/Maddaren/UniqueDropsForever/releases/tag/v0.36.0-beta).
2. Extract it into `World of Warcraft/_forever_/Interface/AddOns`. The extracted folder should be named `UniqueDropsForever`.
3. Restart WoW or type `/reload`, then enable **Unique Drops Forever (BETA)** in the AddOns list.

## Use the addon

- **Database.** Left-click the minimap button. Choose **NPCs** or **Items**, then search by name, tag, or exact ID such as `#2592`. Try `staff + 20-35` or `Westfall + Beast + 16-18`.
- **Filters and sorting.** Use **Filters** to choose item type, equip slot, rarity, level, or quest item visibility. NPC filters cover creature type, faction, zone, and level. Click a column heading to sort, or click **Lock** to choose which columns are visible.
- **Loot and sources.** Right-click the minimap button or use the satchel beside your target frame. Click an item to open its NPC sources and sort them by **Chance**. Shift-left-click an item to put its link in the chat draft. Click an item link in chat, then **See in DB**, to open it in the addon.
- **Settings.** Assign a loot window keybind, resize the windows, or turn on NPC model previews. The **About** tab has in-game instructions.

## Beta data

Loot relationships and estimates use Classic reference data, so coverage of Forever-specific drops and rates is limited. The beta ships without aggregated player loot observations. Personal loot tracking stays in your WoW saved variables. The addon ZIP includes source credits and license information.

Report bugs with the NPC or item ID and the steps to reproduce them on [GitHub Issues](https://github.com/Maddaren/UniqueDropsForever/issues).

# Unique Drops Forever

Unique Drops Forever is a World of Warcraft Forever addon for finding limited-source drops, browsing NPC loot tables, and comparing reference drop rates with your own loot observations. The database runs inside the addon and works offline during play.

## Install

1. Download the addon ZIP from [Releases](../../releases) when a build is available.
2. Extract the ZIP into `World of Warcraft/_forever_/Interface/AddOns`.
3. Start WoW or /reload and enable **Unique Drops Forever** in the AddOns list.

## Find loot and farming sources

- **Open Database.** Left-click the minimap button and choose **NPCs** or **Items**. Search by name, abbreviation, or numeric ID. Click an NPC to open its loot table. Click an item to see its NPC sources, then click a source to open that NPC's loot table.
- **Jump from chat.** Click an item link in chat, then click **See in DB** above the tooltip to open that item's source list.
- **Search by tag.** In **NPCs**, try `Humanoid` or `Westfall`. Combine tags with `+`, such as `"Westfall" + "Undead"`. The **Zone** column shows the NPC's primary known zone.
- **Sort items by level requirement.** In **Items**, search `dagger` to find daggers by type. Click **Required level** to see the lowest character-level requirements first. Click a heading again to reverse the sort. Use `name:dagger` to search item names.
- **Filter drops.** Click **+ Filters** in Database or **+** beside **Loot filters** in the loot window. Filter by rarity, limited sources, recipes, or unknown and unverified rates. In NPC search, a creature is included when at least one of its drops matches the filters.

## Open the loot window for your target

Right-click the minimap button, click the satchel next to your target frame, or assign a shortcut in **Settings ? Keybinding**. Press the same shortcut again to close the window.

Search within the loot table or switch between the available source tabs, such as **Loot**, **Skinning**, and **Pickpocket**. Use the button beside **Close** to switch between compact and full views. Drag a window's bottom-right grip to resize it. The database hub and loot browser remember their positions.

## Read tooltips and drop rates

Hover over an NPC to see limited-source drops, estimated junk loot value per kill, and featured bind-on-equip drops. Hold **Shift** for the expanded bind-on-equip list. In **Settings**, you can choose which tooltip sections appear, change the font size and window appearance, or open **Advanced settings** for rarity, source-count, and display limits.

| Marker | Meaning |
| --- | --- |
| **[P]** | Your recorded loot samples |
| **[WF]** | WoW Forever reference rates |
| **[CE]** | Classic or baseline estimates |
| **?** | Unknown drop chance |

Turn on **Tracking** in the loot browser for your kill and sample counts. The addon records supported, readable solo loot and stores your personal loot history locally.

See **About** in the addon for a quick in-game guide. Data-source credits and license notices accompany the addon download.

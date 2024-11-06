---
title:  "CraftTweaker Enchantment Wrapper"
taxonomy: personal
date: 2024-05-17
last_modified_at: 2024-10-21
---
#### Languages/Tools Used
ZenScript (Minecraft)
#### Responsibilities
Implementation of wrapper item for enchanted items
#### Description
This is a set of scripts for the game Minecraft on version 1.12.2. It adds a wrapper around enchanted items to fix ID issues that can be caused by changing out/adding mods in a modded Minecraft game. These ID issues would normally cause players to obtain items without the intended enchants[^1]. The wrapper acts as a workaround for the reliance on world-specific registry mappings. There is a user-friendly recipe view provided for each wrapper item to communicate its use to the player.

This tool was developed with modpack[^2] authors in mind. Uses ZenScript, a custom scripting language for the mod CraftTweaker, which loads user-defined scripts for Minecraft.

Explanation - [here](https://github.com/jchung01/CT-EnchantWrapper?tab=readme-ov-file#motive) \
Repo - [github.com/jchung01/CT-EnchantWrapper](https://github.com/jchung01/CT-EnchantWrapper)

[^1]: Enchants/Enchantments: Upgrades that enhance the item in some way
[^2]: Modpack: A collection of mods that run on a modloader for Minecraft, created by an author. Often, the author includes custom scripts or config changes to alter gameplay progression and enhance the user's experience.
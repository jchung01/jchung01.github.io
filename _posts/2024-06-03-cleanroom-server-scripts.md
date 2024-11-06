---
title:  "Cleanroom Server Start Scripts"
taxonomy: personal
date: 2024-06-03
last_modified_at: 2024-10-21
---
#### Languages/Tools Used
Powershell, Bash
#### Responsibilities
Development of flexible, multi-platform scripts to start server
#### Description
Installs and runs a modded server for the game Minecraft Java on version 1.12.2. Written in both Powershell and Bash so Windows and Linux work with it. Includes settings for the user to edit, if needed, such as launch arguments, modloader version, and crash recovery.

To load mods on a Minecraft server, a modloader is necessary: the only one that used to exist was Forge. A newer modloader called Cleanroom loader is in development but in a working state, so there is demand by users for a server that can run Cleanroom. Many other public scripts exist to run a modded Minecraft server easily, but none supported Cleanroom, so I made this for ease of installation.
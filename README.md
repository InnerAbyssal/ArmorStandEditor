<div align="center">

<img src="https://github.com/Wolfieheart/ArmorStandEditor/blob/master/ArmorStandEditorHeader.png" />

[![Build Status](https://github.com/Wolfst0rm/ArmorStandEditor/actions/workflows/maven-publish.yml/badge.svg?style=flat)](https://github.com/Wolfst0rm/ArmorStandEditor/actions/workflows/maven-publish.yml)
[![Maintainability Rating](https://sonarcloud.io/api/project_badges/measure?project=wolfieheart_ArmorStandEditor&metric=sqale_rating&style=flat)](https://sonarcloud.io/summary/new_code?id=wolfieheart_ArmorStandEditor)  
[![CodeFactor](https://www.codefactor.io/repository/github/wolfieheart/armorstandeditor/badge?style=flat)](https://www.codefactor.io/repository/github/wolfieheart/armorstandeditor)
[![Scanned with Sonarcloud](https://img.shields.io/badge/Scanned%20With-Sonarcloud-orange?style=flat&logo=sonarcloud)](https://sonarcloud.io/summary/new_code?id=Wolfst0rm_ArmorStandEditor)  
[![wakatime](https://wakatime.com/badge/github/Wolfst0rm/ArmorStandEditor.svg?style=flat)](https://wakatime.com/badge/github/Wolfst0rm/ArmorStandEditor)
[![Compatibility/GetBukkit](https://img.shields.io/badge/Compatability-Paper%2C%20Spigot%2C%20Bukkit%20etc.%20(GetBukkit.org)-yellowgreen?style=flat)](https://getbukkit.org/)
[![License](https://img.shields.io/badge/Licence-GNU%20Public%20V3%20-red?style=flat)](https://github.com/Wolfst0rm/ArmorStandEditor/LICENSE.md)
[![Support Discord](https://dcbadge.vercel.app/api/server/3BbJKWpTCj?style=flat)](https://discord.gg/3BbJKWpTCj)

ArmorStandEditor is a plugin for [Spigot](https://www.spigotmc.org/resources/armorstandeditor-reborn.94503/) / [Paper, All related forks](https://papermc.io/downloads/paper) / [Folia etc.](https://github.com/PaperMC/Folia)  to allow players in survival to easily edit armor stand pose and attributes.

</div>

## Credits

* RypoFalem for the original version of this plugin. Thank you for all your hard work (Archived on this repository on the branch [Original-Version](https://github.com/Wolfst0rm/ArmorStandEditor/tree/Original-Version) )
* Anyone who has contributed to this project with tests, issues, code reviews etc. Thank you!
* Shamblecraft for using the plugin originally and giving me the idea to maintain it.

## Downloads
Downloads for Version 1.17 and higher can be obtained from the [download page](https://www.spigotmc.org/resources/armorstandeditor-reborn.94503/) or our [release tracker](https://github.com/Wolfst0rm/ArmorStandEditor/releases) here on GitHub.
For versions older than 1.17, then please use [the original versions download page](https://www.spigotmc.org/resources/armor-stand-editor-dead.7688/).

The Latest Downloads Shortcut Links:
* [ArmorStandEditor-Last (Unstable)](https://github.com/Wolfst0rm/ArmorStandEditor/actions) 
  - **Use these at your own risk. Limited Support is provided for testing purposes**
* 1.20 - Not yet available
   * [Spigot Redirect to the latest release](https://www.spigotmc.org/resources/armorstandeditor-reborn.94503/) 
   * [Modrinth Redirect to the latest Release](https://modrinth.com/plugin/armorstandeditor-reborn)
* 1.19 to 1.19.4 
   * [Spigot/Github](https://github.com/Wolfieheart/ArmorStandEditor/releases/tag/1.19.4-41)  
   * [Modrinth](https://modrinth.com/plugin/armorstandeditor-reborn/version/1.19.4-41)
* 1.18 to 1.18.2
   * [Spigot/Github](https://github.com/Wolfieheart/ArmorStandEditor/releases/tag/1.18.2-34.2)
   * [Modrinth](https://modrinth.com/plugin/armorstandeditor-reborn/version/1.18.2-34.2)
* 1.17 to 1.17.1
    * [Spigot/Github](https://github.com/Wolfst0rm/ArmorStandEditor/releases/tag/1.17.1-30)
    * [Modrinth](https://modrinth.com/plugin/armorstandeditor-reborn/version/1.17-30)
* 1.16 to 1.16.5
    * [Spigot/Github](https://www.spigotmc.org/resources/armor-stand-editor-dead.7688/download?version=342891)
    * [Modrinth](https://modrinth.com/plugin/armorstandeditor-reborn/version/1.16-25)
* [1.14 to 1.14.4](https://www.spigotmc.org/resources/armor-stand-editor-dead.7688/download?version=299267)
* [1.13 to 1.13.2](https://www.spigotmc.org/resources/armor-stand-editor-dead.7688/download?version=235185)
* [1.11 to 1.11.2](https://www.spigotmc.org/resources/armor-stand-editor-dead.7688/download?version=152723)
* [1.10 to 1.10.2](https://www.spigotmc.org/resources/armor-stand-editor-dead.7688/download?version=124213)
* [1.9 to 1.9.4](https://www.spigotmc.org/resources/armor-stand-editor-dead.7688/download?version=92457)
* [1.8](https://www.spigotmc.org/resources/armor-stand-editor-dead.7688/download?version=29676)

**NOTE:** The 1.17 Versions introduce NMS Version Checks and will not load on versions older than 1.13.

It will also advise that if you are on 1.13 to 1.16, that you update to 1.17.x or Higher. This will be
subject to change in the future. The minimum enforced API Version is 1.13.

## Features
* Editing ArmorStands with no commands required
* Rotation of all ArmorStand Parts along each axis
* Rotation of entire ArmorStand after Placement. Supported by Crouching and Scrolling, so you never have to open the menu
* Finer Adjustment to allow for Fine-Tuning of Positions.
* Coarser Adjustments to allow you to quickly to get to the intended position
* Toggles for: Disabling Slots, Invisibility, Gravity, Base Plates, Size (Normal and Small)
* Copying and Pasting ArmorStand Settings between ArmorStandEditor in a Survival Friendly way
* Storage of Copied Settings in one of 9 available slots.
* Naming of ArmorStands through the use of Vanilla Name tags, with colored name support
* Multiple Language Support through the use of community translations
* Respects multiple protection plugins: WorldGuard, Towny, GriefPrevention, Residence etc.
* Targeting of an ArmorStand by pressing F with the tool in your hand
* Glowing ArmorStand to signify Targeting and Slot Disables through the use of Scoreboards.
* Folia Support (as of 1.19.4)

## Support
Support for ArmorStandEditor is provided:
* For API-Versions Higher than 1.13
* For Latest Release and Unstable versions of the Plugin

If there are issues with the plugin on the latest release, you can report them [here](https://github.com/Wolfst0rm/ArmorStandEditor/issues/new?assignees=&labels=P1%3A+To+Be+Tested&template=behaviour-bug.yml).
If there are new feature requests, you can ask them to be implemented [here](https://github.com/Wolfst0rm/ArmorStandEditor/issues/new?assignees=&labels=&template=feature-request.yml).

**NOTE:** Bugs are also first tested to ensure that they can be reproduced according to the reported steps. If they can not, we will ask for more info.

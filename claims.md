---
layout: default
title: Claiming Land
nav_order: 6
permalink: /claims/
---

# Lands
A more detailed list of commands can be found here: [Lands Wiki](https://wiki.helpch.at/glares-plugins/guilds-w.i.p-migration/commands-and-permissions)
{: .fs-5 .fw-300 }

{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

---

## Getting Started
1. Create a land using `/land create <name>`. This should automatically claim the surrounding 9 chunks around where you currently are at no cost.
2. To expand your current land you can use `/land view` and press F3 + G to see both the claimed and unclaimed chunks.
3. Now move yourself into an unclaimed chunk and you use `/land claim` to claim it. It's worth noting that you can't claim within 1 chunk of another claim which you don't have permission for.
4. The more you claim the higher the cost per chunk will get. You can see your land balance with `/land balance` and you can add to the balance with `/land deposit <amount>`.
5. To add other players to your land use `/land trust <player>`.
6. For those with multiple lands available you can repeat the process for each land you have available and use `/land edit <land>` to select the land you want to use.

### Manage role permissions for land members
Within the lands menu you can edit both action flags and management flags. Action flags control what players can do within your claim such as breaking blocks or opening chests. Management flags control how other players can manage your land.
- /lands > select a land > roles > select a role

From here you can select either action flags or management flags and toggle each option.\
You can also edit the existing roles or add new ones.

This is important if you want to give other players permission to claim next to you, this is where you can find that setting.

### Promoting or demoting land members
You can manage which roles each player has by left clicking the player name to promote or right clicking to demote.
- /lands > select a land > trusted players

### Land flags
Some of these natural flags will work and they apply to the whole claim.
- /lands > select a land > natural flags

The following have been tested to work, the others may or may not work:
- Monster spawning
- Animal spawning
- Plant growth

The following are disabled globally so they can't be toggled:
- TNT block damage
- Entity griefing

### Making sub-claims
This is possible, you can have up to 16 areas within a land each with their own trusted players and permissions. It's quite complex so I would suggest checking the wiki. The basics involve using `/land selection`, selecting two corners one high one low then you can use `/land assign <name>` to assign it to its own area within the land. Now you can manage the area by going to:
- /lands > select a land > areas

## Command List
- **/lands, /l** - Open the lands menu. You can also `/l` with any of the following commands.
- **/lands create \<name>** - Create a new land.
- **/lands claim, /lands unclaim** - Claim the chunk you're currently standing in.
- **/lands claim auto, /lands unclaim auto** - These commands will allow you to claim or unclaim automatically by walking through each chunk.
- **/lands edit \<name>** - Switch which land you want to perform commands with.
- **/lands trust \<player>** - Give another player trust within a claim. Default is member role.
- **/lands leave \<name>** - Leave a land you were invited to join.
- **/lands setspawn** - Set the land spawn.
- **/lands spawn** - Teleport to a land spawn.
- **/lands view** - See the claim borders.
- **/lands withdraw \<amount>** - Move money from the land bank to your personal money.
- **/lands deposit \<amount>** - Move your personal money to the land bank.


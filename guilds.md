---
layout: default
title: Guilds
nav_order: 7
permalink: /guilds/
---

last updated on {{ page.last_modified_at | date: '%d %b %Y' }}
{: .fs-2 .fw-300 .text-right }

# Guilds
A more detailed list of commands can be found here: [Guilds Wiki](https://wiki.helpch.at/glares-plugins/guilds-w.i.p-migration/commands-and-permissions)
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

1. Use the command `/guild create <name>` to create and guild, it does however cost 2500 in game money to do this and the name of the guild will have a character limit.
2. Once you have a guild you can invite other players to join with `/guild invite <player>`.
3. After you invite someone you can choose to promote them to a higher rank with `/guild promote <player>`. The higher the rank the more permissions they have within the guild.
4. You can also add other guilds as an ally with `/guild ally add <guild>`. This will disable pvp between all guild members that are allies.
5. Once you have an ally you can toggle ally chat `/guild ac` or use `/guild ac <message>` to send a message without toggling chat. This chat is private and only guild members can see it.
6. You also have the option to chat to just your own guild members using `/guild gc` or `/guild gc <message>`.

---

## Command List
- **/guild, /g** - Access the guild menu. You can also `/g` with any of the following commands.
- **/guild create \<name>** - Create a guild.
- **/guild invite \<player>** - Add another player to your guild.
- **/guild accept \<name>** - Accept an invite from a guild.
- **/guild decline \<name>** - Reject an invite from a guild.
- **/guild promote \<player>** - Promote a guild members rank. Give them access to more permissions.
- **/guild demote \<player>** - Demote a guild members rank. Give them access to more permissions.
- **/guild request \<guild>** - Request to join a guild.
- **/guild leave** - Leave your current guild.
- **/guild gc** - Toggle guild chat.
- **/guild ac** - Toggle ally chat.
- **/guild list** - View a list of all guilds.
- **/guild vault** - Access the guild vault, a private shared inventory.
- **/guild buff** - Access a variety of short period effects you can purchase to give guild members.
- **/guild upgrade** - Upgrade the guild to a higher tier and unlock more features.

### Ally Commands
- **/guild ally add \<guild>** - Send an ally request to another guild.
- **/guild ally accept \<guild>** - Accept an ally invite from another guild.
- **/guild ally decline \<guild>** - Reject an ally request from another guild.
- **/guild ally remove \<guild>** - Remove any of your current allies.
- **/guild ally list** - List all the current allies of your guild.

### Guild Home
- **/guild sethome** - Set the guild home to your current location.
- **/guild delhome** - Remove the guild home.
- **/guild home** - Teleport to the guild home.

### Guild MOTD
- **/guild motd set \<motd>** - Set a message to appear on log in to all guild members.
- **/guild motd remove** - Remove the guild MOTD.
- **/guild motd** - View the current guild MOTD.

### Guild Bank
- **/guild bank balance** - Check the current balance of your guild bank.
- **/guild bank deposit \<amount>** - Move money from your balance into your guild bank.
- **/guild bank withdraw \<amount>** - Take money from your guild bank and put it back into your personal balance.

---
layout: default
title: XP
parent: Utility
nav_order: 1
---

# XP
Beemo's XP system allows for members to gain experience as they participate in the server via text & voice channels.

---

## About

Users are able to gain XP through both text and voice channels, with customisable curves and role rewards for levels. Servers can add roles to be rewarded at different level milestones and benefit from an intregrated XP leaderboard.

If enabled alongside XP, users will also gain Honey at the same rate, which is consumable in a Honey role shop. See https://docs.beemo.gg/utility/honey for more information on the Honey shop.

## Commands

| Command                 | Description                                                                                                                                                                                                                                     | Usage                                      |
|-------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------|
| xp                      | Enables or disables the XP system.                                                                                                                                                                                                              | /xp (enable/disable)                       |
| xp rolereward           | Adds or removes the specified role as an XP role reward for the level specified. You do not need to specify the role if you are removing the role reward.                                                                                       | /xp rolereward (level) (role name/id)      |
| xp rolerewards          | Lists the current XP role rewards for the server.                                                                                                                                                                                               | /xp rolerewards                            |
| xp reset                | Resets the specified user's XP on the server. Replace user with all to reset the server's XP. Specify a role to reset all users with a role.                                                                                                    | /xp reset (user mention/role name/id)      |
| xp set                  | Sets the specified user's XP to the new XP amount.                                                                                                                                                                                              | /xp set (user mention/id) (new amount)     |
| xp refreshroles         | Refreshes all of the user's XP role rewards. Use this command after you add or remove xp role rewards from the system.                                                                                                                          | /xp refreshroles                           |
| xp textcooldown         | Sets how often 1 XP / honey can be earned through text channels, in seconds.                                                                                                                                                                    | /xp textcooldown (seconds)                 |
| xp voicecooldown        | Sets how often 1 XP / honey can be earned through voice channels, in seconds.                                                                                                                                                                   | /xp voicecooldown (seconds)                |
| xp blacklistrole        | Adds or removes the specified role as an XP & Honey-blacklisted role.                                                                                                                                                                           | /xp blacklistrole (role name/id)           |
| xp blacklistroles       | List the current XP and honey-blacklisted roles. Users with these roles cannot gain XP or honey.                                                                                                                                                | /xp blacklistedroles                       |
| xp blacklistedchannel   | Adds or removes the specified text or voice channel as an XP and honey-blacklisted channel.                                                                                                                                                     | /xp blacklistchannel (channel name/id)     |
| xp blacklistedchannels  | Lists the current XP and honey-blacklisted text and voice channels.                                                                                                                                                                             | /xp blacklistedchannels                    |
| xp adminrole            | Adds or removes the specified role as an XP and honey admin role.                                                                                                                                                                               | /xp adminrole (role name/id)               |
| xp adminroles           | Lists the current XP and honey admin roles. Users with these roles can use XP and honey admin commands.                                                                                                                                         | /xp adminroles                             |
| xp keepxproles          | Sets if users should keep their previous XP roles when they reach the next role reward.                                                                                                                                                         | /xp keepxproles (yes/no)                   |
| xp resetonleave         | Sets if user XP / honey should be reset upon leaving the server.                                                                                                                                                                                | /xp resetonleave (yes/no)                  |
| xp resetonban           | Sets if user XP / honey should be reset upon being banned from the server.                                                                                                                                                                      | /xp resetonban (yes/no)                    |
| xp notifications        | Sets if a level up notification should be sent when a user levels up.                                                                                                                                                                           | /xp notifications (yes/no)                 |
| xp notificationschannel | Sets the channel to send level up notifications to. Put none for the channel name to remove a set channel. If no channel is specified, the notice will be sent to the user's DMs.                                                               | /xp notificationschannel (channel name/id) |
| xp commandchannel       | Adds or removes the specified text channel as an allowed channel for XP and honey commands.                                                                                                                                                     | /xp commandchannel (channel name/id)       |
| xp commnadchannels      | Lists the current XP and honey command channels.                                                                                                                                                                                                | /xp commandchannels                        |
| xp rankcommandcooldown  | Sets the cooldown in seconds for the /rank command.                                                                                                                                                                                             | /xp rankcommandcooldown (seconds)          |
| xp difficulty           | IMPORTANT: This setting will change the XP curve! Sets the difficulty of the XP system. This modifies the multiplier so that the amount of XP needed to reach the next level is either larger or smaller. The current difficulty is set to 1.0. | /xp difficulty (decimal value)             |
| xp leveltoxpratio       | IMPORTANT: This setting will change the XP curve! Changes the XP level-to-xp ratio to the specified decimal value.                                                                                                                              | /xp leveltoxpratio (decimal value)         |
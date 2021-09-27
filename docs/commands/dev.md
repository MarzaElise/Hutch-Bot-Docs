# Developer Commands

Commands that are mainly related to the bot. Some can only be used by the [bot owner](https://discord.com/users/754557382708822137)

## Botnick

- Invocation : **`h!botnick <new nickname>`**
- Description: Change the bot's nick name in a server
- Aliases: None
- Required Permissions:
    - None
- Cooldown: **`0s`**
!!! info
    This command is restricted to [bot owner](https://discord.com/users/754557382708822137)

## Changelogs

- Invocation : **`h!changelogs`**
- Description: View the changelogs for the latest version. Has subcommands restricted to [bot owner](https://discord.com/users/754557382708822137) that are not documented
- Aliases: None
- Required Permissions:
    - None
- Cooldown: **`5s`**

## Disable

- Invocation : **`h!disable <command name>`**
- Description: Disable a command throughout the entire bot.
- Aliases: None
- Required Permissions:
    - None
- Cooldown: **`0s`**
!!! info
    This command is restricted to [bot owner](https://discord.com/users/754557382708822137)

## Enable

- Invocation : **`h!enable <command name>`**
- Description: Does the opposite of the [disable](#disable) command.
- Aliases: None
- Required Permissions:
    - None
- Cooldown: **`0s`**
!!! info
    This command is restricted to [bot owner](https://discord.com/users/754557382708822137)

## Reboot

- Invocation : **`h!reboot`**
- Description: Restarts the bot by logging it out and re-logging in
- Aliases: **`reboot`** **`restart`**
- Required Permissions:
    - None
- Cooldown: **`0s`**
!!! info
    This command is restricted to [bot owner](https://discord.com/users/754557382708822137)

## Reload

- Invocation : **`h!reload`**
- Description: Reloads all of the categories. faster than [reboot](#reboot) since it doesnt log out
- Aliases: None
- Required Permissions:
    - None
- Cooldown: **`0s`**
!!! info
    This command is restricted to [bot owner](https://discord.com/users/754557382708822137)

## Stats

- Invocation : **`h!reload`**
- Description: Sends the statistics of the bot. No information was stored for this command
- Aliases: None
- Required Permissions:
    - None
- Cooldown: **`5s`**

## Update

- Invocation : **`h!update <new version>`**
- Description: Update the bot's version to the given version
- Aliases: **`update`** **`uv`**
- Required Permissions:
    - None
- Cooldown: **`0s`**
!!! info
    This command is restricted to [bot owner](https://discord.com/users/754557382708822137)

## Report

- Invocation : **`h!report [message]`**
- Description: Use this to contact bot owner to report bugs / suggest stuff if you dont want to join support server
- Aliases: None
- Required Permissions:
    - None
- Cooldown: **`12h`**

## Source

- Invocation : **`h!source <command>`**
- Description: View the source of the given command
- Aliases: None
- Required Permissions:
    - None
- Cooldown: **`10s`**

## Blacklist

- Invocation : **`h!blacklist <member> [reason]`**
- Description: Blacklist a member from using the bot. Currently not implemented
- Aliases: None
- Required Permissions:
    - None
- Cooldown: **`0s`**
!!! info
    This command is restricted to [bot owner](https://discord.com/users/754557382708822137)

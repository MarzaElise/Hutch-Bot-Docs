# Moderation Commands

Essential common commands for moderation purposes

## Ban

- Invocation : **`h!ban <user> [reason]`**
- Description: Ban a member from the server
- Aliases: None
- Required Permissions:
    - **`Ban Members`** -> Obviously **`Ban Members`** permission is needed to ban users
- Cooldown: **`0s`**

## Clear

- Invocation : **`h!clear [amount]`**
- Description: Clear a number of messages from the current channel.
- Aliases: **`purge`** **`clean`** **`clear`**
- Required Permissions:
    - **`Manage Messages`** -> Discord requires **`Manage Messages`** permission to delete other's messages
- Cooldown: **`5s`**

## Kick

- Invocation : **`h!kick <user> [reason]`**
- Description: kick a member from the server. They will be able to join back with another invite
- Aliases: None
- Required Permissions:
    - **`Kick Members`** -> Obviously **`Kick Members`** permission is needed to kick users
- Cooldown: **`0s`**

## Massban

- Invocation : **`h!massban [members]... [reason]`**
- Description: Ban multiple members from the server. If a member is not found, all the text after the member is added to reason
- Aliases: None
- Required Permissions:
    - **`Ban Members`** -> To ban all the members
- Cooldown: **`0s`**

## Rules

- Invocation : **`h!rules`**
- Description: send a set of common
- Aliases: None
- Required Permissions:
    - **`Ban Members`** -> To ban all the members
- Cooldown: **`0s`**

## Slowmode

- Invocation : **`h!slowmode [secs]`**
- Description: Set an amount of slowmode to a channel. note that this should be in seconds.
- Aliases: **`slowmode`** **`sm`** **`setdelay`** **`delay`** **`slow`**
- Required Permissions:
    - **`Manage Channel`** -> Discord requires it to edit a channel
- Cooldown: **`3s`**

## Unban

- Invocation : **`h!unban <member> [reason]`**
- Description: Unban a previously banned member
- Aliases: None
- Required Permissions:
    - **`Unban Members`** -> Discord's requirement to unban :shrug:
- Cooldown: **`0s`**

## Whois

- Invocation : **`h!whois [member]`**
- Description: Display information about a user. defaults to yourself when no user given. Note that None of these information are stored. they are directly taken from discord's API
- Aliases: **`whois`** **`user`** **`userinfo`** **`about`** *``who``*
- Required Permissions:
    - None
- Cooldown: **`15s`**

---
hide:
    - navigation
---

# Latest Features

Some of the features added/removed/updated on the last update of the bot

*This is for the bot version 3.6.0*

## New Commands

*New commands that were added in the latest release*

- RTFM

    - RTFM stands for "**R**ead **T**he **F**ucking **M**anual"
    - You can use this to search for a specific term in a specific documentation
    - Currently supported docs:

        - [`diskord`](https://diskord.rtfd.io) - The library hutch bot uses
        - [`discord.py`](https://discordpy.rtfd.io) - The library hutch bot was previously using
        - [`jishaku`](https://jishaku.rtfd.io) - A debugging library used with discord.py and diskord

    - Documentation can be found [here](./../commands/misc.md#rtfm)

## Updated Commands

*Existing commands that were updated in the latest release*

- Embed

    - Embed flag parsing was changed from the `--flag value` syntax to `flag: value` syntax
    - Example usage: `h!embed title: Title Text description: This is description`

- Chat

    - You can now chat continuosly with the bot instead of having to do the `h!chat` command each and every time
    - More customization is done to the response returnd, for example favourite actor, actress etc

## Removed Commands

*Commands that were removed in the latest release*

- NSFW

    - Made it for fun but it seemed to be cringe as fuck and pointless
    - Many personal reasons such as me not being able to showcase my bot to people I know in real life

## Extra

*Extra information about the latest release*

- Hutch Bot now uses the [`diskord`](https://pypi.org/project/diskord) module.
- Something I said i'll do in the previous version, moving to databases, will be done in upcoming versions
- I have yet to implement slash commands, context menus and buttons
- Bot version updated to **3.6.0**
- Source code can be viewed [`here`](https://github.com/MarzaElise/Hutch-Bot)
- Caching

    - I have decided to cache some expensive stuff.
    - From now, the bot wont create useless invites when the [`h!servers`](./../commands/misc.md#server) command is used
    - Hutch now also caches the reddit posts returned in the [`h!reddit`](./../commands/fun.md#reddit) command

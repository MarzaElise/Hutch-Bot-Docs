# Fun Commands

Some commands for you to enjoy and spend your time happily

## Binary

- Invocation : **`h!binary <text>`**
- Description: Turn a text to binary
- Aliases: **`b`** **`turnbinary`** **`binary`**
- Required Permissions:
    - None
- Cooldown: **`5s`** per **`member`**

## Chat

- Invocation : **`h!chat <text>`**
- Description: Chat with the bot! powered by [Random Stuff API](https://api-info.pgamerx.com/)
- Aliases: **`chat`** **`c`** **`talk`**
- Required Permissions:
    - None
- Cooldown: **`2 s`** per **`member`**

## Coin Flip

- Invocation : **`h!coinflip`**
- Description: Flip a coin and get a random result
- Aliases: **`flip`** **`coin`** **`coinflip`**
- Required Permissions:
    - None
- Cooldown: **`5s`** per **`member`**

## Dm

- Invocation : **`h!dm <member> <text to dm>`**
- Description: DM a member of your choice through the bot (requires the member you're trying to DM to be opted into the DM command)
- Aliases: None  
- Required Permissions:
    - None
- Cooldown: **`20s`** per **`member`**

    ### Dm Opt

    - Invocation : **`h!dm opt <opting position>`** (`in` or `out`)
    - Description: Sub command of [`Dm`](#dm). lets you opt out or opt into the DM command. Opting out will result in not receiving any DMs.
    - Aliases: None
    - Required Permissions:
        - None
    - Cooldown: **`12h`** per **`member`**

## Echo

- Invocation : **`h!echo [channel] <msg>`**
- Description: echo a message to a specific channel if provided or the current channel if not provided
- Aliases: **`say`** **`echo`**
- Required Permissions:
    - None
- Cooldown: **`5s`** per **`member`**

## Eightball

- Invocation : **`h!8ball <question>`**
- Description: Get a random answer to a question. Works well for the times when you dont  trust your friend's choice
- Aliases: **`eightball`** **`8ball`**
- Required Permissions:
    - None
- Cooldown: **`5s`** per **`member`**

## Fact

- Invocation : **`h!fact`**
- Description: Get a random fact. powered by [randomness api](https://randomness-apip.herokuapp.com) (also made by me)
- Aliases: **`fact`** **`funfact`** **`facts`**
- Required Permissions:
    - None
- Cooldown: **`5s`** per **`member`**

## Image

- Invocation : **`h!image [image name]`**
- Description: Get a random image from a list of limited image categories
- Aliases: **`image`** **`search`** **`searchimage`**
- Required Permissions:
    - None
- Cooldown: **`10s`** per **`member`**

## Meme

- Invocation : **`h!meme`**
- Description: generate a random meme. powered by [some random api](https://some-random-api.ml)
- Aliases: **`meme`** **`memey`**
- Required Permissions:
    - **`Permission_name`** - Reason
- Cooldown: **`5s`** per **`member`**

## Poll

- Invocation : **`h!poll <title> [options...]`**
- Description: A simple poll command to have a voting make a decision on something
- Aliases: **`poll`** **`polls`** **`p`**
- Required Stuff:
    - **`NSFW channel`** - to send the nsfw content
- Cooldown: **`5s`** per **`member`**

## Reddit

- Invocation : **`h!reddit [subreddit]`**
- Description: retreive a meme from the given subreddit that defaults to [r/memes](https://reddit.com/r/memes). NSFW subreddits would not work. Note that you should remove `r/` from the reddit name. For example, `r/memes` -> `memes`
- Aliases: **`reddit`** **`red`** **`r`**
- Required Stuff:
    - None
- Cooldown: **`5s`** per **`member`**

## Repeat

- Invocation : **`h!repeat <amount> <msg>`**
- Description: Repeat a given `msg` to an amount of times that doesnt exceed `7`
- Aliases: **`repeat`** **`send`**
- Required Permissions:
    - None
- Cooldown: **`20s`** per **`member`**

## Web

- Invocation : **`h!web`**
- Description: A random website link generated using [randomness api](https://randomness-api.herokuapp.com) (Use at your own risk)
- Aliases: **`web`** **`random`** **`website`** **`uselessweb`** **`useless`**
- Required Permissions:
    - None
- Cooldown: **`10s`** per **`member`**

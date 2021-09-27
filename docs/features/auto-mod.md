# Auto Moderation

Hutch Bot currently contains two main automoderation sytems.

1. Swear Word Filter
    - Hutch Bot has a nice swear word filtered with some common words whitelisted so your server doesnt get boring!
    - It currently doesnt support a way to turn this feature off.

2. ToS breaking

    One of the main problems many servers struggle with is banning ToS violators.

    Banning ToS breakers manually can be exhausting, thus Hutch Bot's moderation system takes a small part in it.

    1. Mentioning Everyone

        - This is the only feature in this section as of writing this. Basically, this feature will `kick` any users who mention `@everyone` or `@here` without the proper permissions.

        - Bypassing permissions is also against the discord's ToS. This will kick the user instead of banning them since this might get exploited

        - Currently, this feature cannot be disabled per server.

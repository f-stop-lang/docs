# Roo


```prolog
OPEN URL "https://cdn.discordapp.com/attachments/381963689470984203/861290980397547520/The_Anime_Bot_resize.png" AS rooPog
OPEN URL "https://cdn.discordapp.com/emojis/597589960270544916.png?v=1" AS rooBless
OPEN URL "https://cdn.discordapp.com/emojis/511919340925354005.png?v=1" AS rooDevil

NEW [] AS roo

RESIZE rooPog (800, 800)

ITER ([rooPog, rooBless, rooDevil] AS amogus) -> (RESIZE amogus SIZE rooPog APPEND amogus TO roo)
SAVE roo STREAM "GIF" DURATION 10 LOOP 0
```
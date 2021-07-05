# More Roo


```prolog
OPEN URL "https://cdn.discordapp.com/emojis/597589960270544916.png?v=1" AS rooBless
OPEN URL "https://cdn.discordapp.com/emojis/511919340925354005.png?v=1" AS rooDevil

NEW [] AS roo

RESIZE rooDevil (200, 200)
RESIZE rooBless SIZE rooDevil
APPEND rooBless TO roo
MIRROR rooDevil
APPEND rooDevil TO roo
MIRROR rooBless
APPEND rooBless TO roo
MIRROR rooDevil
APPEND rooDevil TO roo
ROTATE rooBless 180
ROTATE rooDevil 180
APPEND rooBless TO roo
MIRROR rooDevil
APPEND rooDevil TO roo
MIRROR rooBless
APPEND rooBless TO roo
MIRROR rooDevil
APPEND rooDevil TO roo
SAVE roo STREAM "GIF" DURATION 0 LOOP 0
```
# emoji emoji emoji

Generate emoji table for your lua module.

Emoji names match the name used by Github.
---
to generate lua module, run `python3 src/generate.py`

👍 👍 👍 👍 👍 👍 👍 👍 👍 👍 👍 👍
## example
```lua 
local emoji = require("emoji")
-- all are the same
print(emoji.emoji("grin"))
print(emoji.emoji(":grin"))
print(emoji.emoji(":grin:"))
```

## LICENSE
[![img]][pbd]

[img]:https://licensebuttons.net/p/zero/1.0/88x31.png
[pbd]:https://creativecommons.org/publicdomain/zero/1.0/

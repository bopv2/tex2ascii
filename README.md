# tex2ascii
Text 2 ASCII for ROBLOX Lua

# How to use?
1. On your game's explorer head over to wherever you want to place the script and right click on the parent > Import from File... > Select tex2ascii.lua
2. Go to your script that will request a function from the modulescript and require the modulescript (ex. `local tex2ascii = require(game.ServerScriptService.tex2ascii)`)
3. Done! Now use it like this: `print(tex2ascii.convert("bblahblahbblah"))`

# Typical ohio code:
```lua
local tex2ascii = require(game.Workspace.tex2ascii)

print(tex2ascii.convert("legoooo"))
```

# **DOESNT CONVERT NUMBERS/SYMBOLS! ONLY ENGLISH CHARACTERS (CAPS/NO CAPS)**

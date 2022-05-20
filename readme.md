# SCRIPT

```lua
local branch = "master"
local file = "main"

function execUI()
    loadstring(game:HttpGetAsync(("https://raw.githubusercontent.com/grabbingLemons/roactMakeChar/$s/script/$s.lua"):format(branch, choice)), file .. '.lua')()
end


execUI()
```


# USAGE

Allows me to easily change between chars using a roact ui


## Current Issues:

```
 [*] Does not execute the loadstring I guess?
```
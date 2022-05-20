# SCRIPT

```lua
local branch = "main"
local file = ""

function execUI()
    loadstring(game:HttpGetAsync(("https://raw.githubusercontent.com/grabbingLemons/roactMakeChar/%s/%.lua"):format(branch, choice)), file .. '.lua')()
end


execUI()
```


# USAGE

Allows me to easily change between chars using a roact ui


## Current Issues:

```
 [*] Does not execute the loadstring I guess?
```
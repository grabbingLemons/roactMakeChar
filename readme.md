# SCRIPT
#### Ver 1.0.4


```lua
local branch = "master"
local file = "main"

function execUI()
    loadstring(game:HttpGetAsync(("https://raw.githubusercontent.com/grabbingLemons/roactMakeChar/%s/script/%s.lua"):format(branch, file)), file .. '.lua')()
end

execUI()
```


# USAGE

Allows me to easily change between chars using a roact ui


## Current Issues:

```
 [%] None for now
```
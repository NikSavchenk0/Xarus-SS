# Script
```lua
_G.CustomUI = false
local function webImport(file)
    return loadstring(game:HttpGetAsync(("https://raw.githubusercontent.com/NikSavchenko3/Xarus-SS/main/Xarus%20SS%20(2).lua"):format(owner, branch, file)), file .. '.lua')()
end
```
# Xarus SS
Xarus SS - this is free server side executor.

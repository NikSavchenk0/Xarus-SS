# Script
```lua
_G.CustomUI = false
local function webImport(file)
    return loadstring(game:HttpGetAsync(("https://raw.githubusercontent.com/NikSavchenko3/Xarus-SS/main/Xarus%20SS%20(2).lua"):format(owner, branch, file)), file .. '.lua')()
end
```
# Xarus SS
Xarus SS - this is free server side executor.
<p align="center">
    <img src="https://media.discordapp.net/attachments/740850328316149760/875766210757795920/xarusss.png"/>
    </br>
    <img src="https://cdn.discordapp.com/attachments/694726636138004593/742408546334933002/unknown.png" width="677px"/>
</p>
<details><summary>From the backend</summary>
This is how commands are called from scripts or automations.

```yaml
service: browser_mod.<command>
data:
  parameter: value
  other_parameter: other value
  deviceID:
    - device1
    - device2
```

Note that `parameter` and `other_parameter` etc. depends on the command, but `deviceID` (which is optional) is available for all commands unless otherwise stated.

`deviceID` shall be a list of device IDs that the command will be run on. \
If `deviceID` is not specified, the command will be run on ALL connected _devices_.

</details>
_sorry time out_

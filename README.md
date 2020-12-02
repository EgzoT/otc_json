# otc_json

JSON library module for OTClient

# Information

This module use rxi/json.lua library: https://github.com/rxi/json.lua

# How to add?

## Download

Download ZIP from site

or

Clone repository using git command (with git submodules to download json.lua)

```
git clone --recurse-submodules --remote-submodules https://github.com/EgzoT/otc_json.git
```

## Next

Add folder [otc_json] to "mods" or "modules" folder (recommended "mods" folder) in your main OTClient folder.

# Example usage

## Encode JSON

```lua
print(JSON.encode({test = 2}))
```

## Decode JSON

```lua
print(JSON.decode('{"test": 2}')['test'])
```

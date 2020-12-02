# otc_json

JSON library module for OTClient

# How to add?

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

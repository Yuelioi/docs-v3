---
display_name: Add
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Map](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Map)

Adds a key and value to the map. If something already uses the provided key it will be overwritten with the new value.
After calling Key is guaranteed to be associated with Value until a subsequent mutation of the Map.

Target is Blueprint Map Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| wildcard | Target Map | The map to add the key and value to |
| wildcard | Key | The key that will be used to look the value up |
| wildcard | Value | The value to be retrieved later |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

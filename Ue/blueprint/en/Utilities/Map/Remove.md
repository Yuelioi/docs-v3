---
display_name: Remove
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Map](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Map)

Removes a key and its associated value from the map.

Target is Blueprint Map Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| wildcard | Target Map | The map to remove the key and its associated value from |
| wildcard | Key | The key that will be used to look the value up |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if an item was removed (False indicates nothing in the map uses the provided key) |

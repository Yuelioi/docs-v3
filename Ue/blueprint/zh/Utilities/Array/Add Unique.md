---
display_name: Add Unique
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Array](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Array)

Add item to array (unique)

Target is Kismet Array Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| wildcard | Target Array | The array to add item to |
| wildcard | New Item | The item to add to the array |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | The index of the newly added item, or INDEX_NONE if the item is already present in the array |

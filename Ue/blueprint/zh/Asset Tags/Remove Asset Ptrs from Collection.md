---
display_name: Remove Asset Ptrs from Collection
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Tags](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetTags)

Remove the given assets from the given collection.

Target is Asset Tags Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | Name of the collection to modify. |
| object | Asset Ptrs | Assets to remove. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the collection was modified, false otherwise (see the output log for details on error). |

---
title: Add Asset Datas to Collection
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Tags](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetTags)

Add the given assets to the given collection.

Target is Asset Tags Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | Name of the collection to modify. |
| struct | Asset Datas | Assets to add. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the collection was modified, false otherwise (see the output log for details on error). |

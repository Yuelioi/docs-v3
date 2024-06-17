---
title: Get Assets by Path (Message)
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Gets asset data for all assets in the supplied folder path

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Package Path | the path to query asset data in (eg, /Game/MyFolder) |
| boolean | Recursive | if true, all supplied paths will be searched recursively |
| boolean | Include Only on Disk Assets | If true, use only DiskGatheredData, do not calculate from UObjects. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Asset Data | the list of assets in this path |
| boolean | Return Value |  |

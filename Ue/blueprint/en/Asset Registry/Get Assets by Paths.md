---
title: Get Assets by Paths
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Gets asset data for all assets in any of the supplied folder paths

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| name | Package Paths | the paths to query asset data in (eg, /Game/MyFolder) |
| boolean | Recursive | if true, all supplied paths will be searched recursively |
| boolean | Include Only on Disk Assets | If true, use only DiskGatheredData, do not calculate from UObjects. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Asset Data | the list of assets in this path |
| boolean | Return Value |  |

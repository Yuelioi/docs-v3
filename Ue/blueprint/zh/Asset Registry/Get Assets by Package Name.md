---
display_name: Get Assets by Package Name
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Gets asset data for the assets in the package with the specified package name

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| name | Package Name | the package name for the requested assets (eg, /Game/MyFolder/MyAsset) |
| boolean | Include Only on Disk Assets | If true, use only DiskGatheredData, do not calculate from UObjects. |
| boolean | Skip ARFiltered Assets | If true, skips Objects that return true for IsAsset but are not assets in the current platform. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Asset Data | the list of assets in this path |
| boolean | Return Value |  |

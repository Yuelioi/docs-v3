---
display_name: Get Assets by Class
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Gets asset data for all assets with the supplied class

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| struct | Class Path Name | the full path of the class name of the assets requested, in a TopLevelAssetPath structure. |
| boolean | Search Sub Classes | if true, all subclasses of the passed in class will be searched as well |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Asset Data | the list of assets in this path |
| boolean | Return Value |  |

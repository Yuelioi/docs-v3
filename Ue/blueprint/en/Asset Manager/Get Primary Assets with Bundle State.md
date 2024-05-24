---
display_name: Get Primary Assets with Bundle State
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetManager)

Returns the list of assets that are in a given bundle state. Required Bundles must be specified
If ExcludedBundles is not empty, it will not return any assets in those bundle states
If ValidTypes is not empty, it will only return assets of those types
If ForceCurrentState is true it will use the current state even if a load is in process

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Required Bundles |  |
| name | Excluded Bundles |  |
| struct | Valid Types |  |
| boolean | Force Current State |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Primary Asset Id List |  |

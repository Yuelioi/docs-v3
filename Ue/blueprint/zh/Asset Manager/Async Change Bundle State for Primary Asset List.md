---
display_name: Async Change Bundle State for Primary Asset List
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetManager)

Change the bundle state of specific assets in PrimaryAssetList.
AddBundles are added to the final state and RemoveBundles are removed, an empty array will make no change.
This will not change the loaded status of primary assets but will load or unload secondary assets based on the bundles.

Target is Async Action Change Primary Asset Bundles

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Primary Asset List |  |
| name | Add Bundles |  |
| name | Remove Bundles |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | Completed |  |

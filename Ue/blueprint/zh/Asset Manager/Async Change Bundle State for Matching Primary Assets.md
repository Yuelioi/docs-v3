---
display_name: Async Change Bundle State for Matching Primary Assets
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetManager)

Change the bundle state of all assets that match OldBundles to instead contain NewBundles.
This will not change the loaded status of primary assets but will load or unload secondary assets based on the bundles.

Target is Async Action Change Primary Asset Bundles

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | New Bundles |  |
| name | Old Bundles |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | Completed |  |

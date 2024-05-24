---
display_name: Is Asset Owned by Cache
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD)

Returns true in case the asset at `AssetPath` is tracked by the cache in any way (persistent asset,
unreferenced or referenced). An example AssetPath would be "/Game/MyTextures/RedBrick.RedBrick".

Target is USD Asset Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| string | Asset Path |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true in case the asset at `AssetPath` is tracked by the cache in any way (persistent asset,unreferenced or referenced). An example AssetPath would be "/Game/MyTextures/RedBrick.RedBrick". |

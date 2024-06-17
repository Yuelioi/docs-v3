---
title: Remove Asset
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Caching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Caching)

If an asset is associated with `Hash`, it will be returned and the asset cache will stop tracking this asset
entirely. Returns nullptr otherwise. See CanRemoveAsset.

WARNING: The asset will still be outer'd to the asset cache, however. The caller is in charge of properly
placing the asset at a new Outer object.

Target is USD Asset Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Hash |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | If an asset is associated with `Hash`, it will be returned and the asset cache will stop tracking this assetentirely. Returns nullptr otherwise. See CanRemoveAsset.WARNING: The asset will still be outer'd to the asset cache, however. The caller is in charge of properlyplacing the asset at a new Outer object. |

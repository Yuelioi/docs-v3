---
title: Get Cached Asset
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Caching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Caching)

Returns an asset associated with a particular `Hash`.
If the asset is persistent, unloaded and the "USD.OnDemandCachedAssetLoading" cvar is true, this may cause the
asset to be read from the asset cache's file on disk.

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
| object | Return Value | Returns an asset associated with a particular `Hash`.If the asset is persistent, unloaded and the "USD.OnDemandCachedAssetLoading" cvar is true, this may cause theasset to be read from the asset cache's file on disk. |

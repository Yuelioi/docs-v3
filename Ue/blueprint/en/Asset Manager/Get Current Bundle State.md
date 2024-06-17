---
title: Get Current Bundle State
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Manager](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetManager)

Returns the list of loaded bundles for a given Primary Asset. This will return false if the asset is not loaded at all.
If ForceCurrentState is true it will return the current state even if a load is in process

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Primary Asset Id |  |
| boolean | Force Current State |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Out Bundles |  |
| boolean | Return Value | Returns the list of loaded bundles for a given Primary Asset. This will return false if the asset is not loaded at all.If ForceCurrentState is true it will return the current state even if a load is in process |

---
title: Can Remove Asset
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Caching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Caching)

Returns true if the asset with the given hash can be removed from the cache. It will return false in case the
asset is still being used, either by another consumer asset or directly by some referencer.

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
| boolean | Return Value | Returns true if the asset with the given hash can be removed from the cache. It will return false in case theasset is still being used, either by another consumer asset or directly by some referencer. |

---
title: Get Hash for Asset
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [USD](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/USD)

Returns the hash associated with an asset, in case we own it. Returns the empty string otherwise.
Note: This has O(1) time complexity.

Target is USD Asset Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Asset |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | Returns the hash associated with an asset, in case we own it. Returns the empty string otherwise.Note: This has O(1) time complexity. |

---
title: Get Data Registry Item From Lookup (experimental)
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataRegistry)

Attempts to get structure data stored in a DataRegistry cache after an async acquire, modifying OutItem if the item is available

Target is Data Registry Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Item Id | Item identifier to lookup in cache |
| struct | Resolved Lookup | Resolved identifier returned by acquire function |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| wildcard | Out Item | This must be the same type as the registry, if the item is found this will be filled in with the found data |
| boolean | Return Value | Returns true if the item was found and OutItem was modified |

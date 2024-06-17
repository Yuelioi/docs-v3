---
title: Get Data Registry Item (experimental)
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataRegistry)

Attempts to get cached structure data stored in a DataRegistry, modifying OutItem if the item is available
(EXPERIMENTAL) this version has an input param and simple bool return

Target is Data Registry Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Item Id | Item identifier to lookup in cache |
| wildcard | Out Item | This must be the same type as the registry, if the item is found this will be filled in with the found data |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Returns true if the item was found and OutItem was modified |

---
title: Find Data Registry Item (experimental)
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataRegistry)

Attempts to get cached structure data stored in a DataRegistry, modifying OutItem if the item is available
(EXPERIMENTAL) this version has an output param and enum result

Target is Data Registry Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Item Id | Item identifier to lookup in cache |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Found | Found the row successfully. |
| exec | Not Found | Failed to find the row. |
| wildcard | Out Item | This must be the same type as the registry, if the item is found this will be filled in with the found data |

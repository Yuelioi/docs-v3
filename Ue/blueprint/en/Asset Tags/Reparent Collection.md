---
title: Reparent Collection
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Tags](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetTags)

Re-parent the given collection.

Target is Asset Tags Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | Name of the collection to re-parent. |
| name | New Parent Name | Name of the new parent collection, or None to have the collection become a root collection. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the collection was renamed, false otherwise (see the output log for details on error). |

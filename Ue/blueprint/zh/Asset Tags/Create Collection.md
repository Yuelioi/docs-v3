---
title: Create Collection
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Tags](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetTags)

Create a new collection with the given name and share type.

Target is Asset Tags Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | Name to give to the collection. |
| enum | Share Type | Whether the collection should be local, private, or shared? |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the collection was created, false otherwise (see the output log for details on error). |

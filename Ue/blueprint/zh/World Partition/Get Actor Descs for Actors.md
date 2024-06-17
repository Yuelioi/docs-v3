---
title: Get Actor Descs for Actors
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [World Partition](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WorldPartition)

Gets all the actor descriptors from the provided actor pointers, which represents descriptors on disk, e.g. will not
reflect properties of unsaved actors.

Target is World Partition Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Actors |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Actor Descs |  |
| boolean | Return Value | True if the operation was successful. |

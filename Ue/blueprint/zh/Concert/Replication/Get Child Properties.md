---
title: Get Child Properties
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Concert](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Concert) > [Replication](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Concert/Replication)

Returns all child properties of Parent that are valid for replicating.

Target is Concert Replication Blueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Parent | The property of which to find child properties |
| class | Class | The class in which to search |
| boolean | Only Direct | Whether you only want direct children of Parent |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | All child properties of Parent that are valid for replicating. |

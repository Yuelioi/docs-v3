---
title: Is Deleted Actor Valid
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Level Snapshots](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LevelSnapshots)

This is called when an actor was removed from the world since the snapshot had been taken.

Target is Level Snapshot Blueprint Filter

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Params |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| enum | Return Value | Whether to track the removed actor |

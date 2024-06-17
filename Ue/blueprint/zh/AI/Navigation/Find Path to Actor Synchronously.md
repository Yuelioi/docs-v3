---
title: Find Path to Actor Synchronously
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Navigation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Navigation)

Finds path instantly, in a FindPath Synchronously. Main advantage over FindPathToLocationSynchronously is that
the resulting path will automatically get updated if goal actor moves more than TetherDistance away from last path node

Target is Navigation System V1

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Path Start |  |
| object | Goal Actor |  |
| real | Tether Distance |  |
| object | Pathfinding Context | could be one of following: NavigationData (like Navmesh actor), Pawn or Controller. This parameter determines parameters of specific pathfinding query |
| class | Filter Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |

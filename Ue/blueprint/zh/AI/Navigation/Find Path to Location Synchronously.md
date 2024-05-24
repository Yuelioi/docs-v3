---
display_name: Find Path to Location Synchronously
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Navigation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Navigation)

Finds path instantly, in a FindPath Synchronously.

Target is Navigation System V1

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Path Start |  |
| vector | Path End |  |
| object | Pathfinding Context | could be one of following: NavigationData (like Navmesh actor), Pawn or Controller. This parameter determines parameters of specific pathfinding query |
| class | Filter Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |

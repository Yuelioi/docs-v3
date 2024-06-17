---
title: Get Distance to Stage Geometry
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [NDisplay](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NDisplay) > [Stage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NDisplay/Stage)

Gets the distance from a world position to the stage's geometry along the specified direction, if there is an intersection

Target is nDisplay Root Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| vector | World Position | The world position to measure the distance from |
| vector | World Direction | The direction to find the distance to the geometry along |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Out Distance | The distance to the stage geometry from the specified point |
| boolean | Return Value | True if an intersection point from WorldPosition along WorldDirection was found, false if not |

---
title: Convert World Location To Screen Location
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Player)

Convert a World Space 3D position into a 2D Screen Space position.

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| vector | World Location |  |
| boolean | Player Viewport Relative |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Screen Location |  |
| boolean | Return Value | true if the world coordinate was successfully projected to the screen. |

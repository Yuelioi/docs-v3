---
title: Project World to Screen
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Camera)

Transforms the given 3D world-space point into a its 2D screen space coordinate.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Player | Project using this player's view. |
| vector | World Position | World position to project. |
| boolean | Player Viewport Relative | Should this be relative to the player viewport subregion (useful when using player attached widgets in split screen) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Screen Position | (out) Corresponding 2D position in screen space |
| boolean | Return Value |  |

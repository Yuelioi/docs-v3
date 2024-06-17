---
title: ScreenToAbsolute
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface) > [Geometry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface/Geometry)

Translates a screen position in pixels into absolute application coordinates.
If bIncludeWindowPosition is true, then this method will also remove the game window's position (useful when in windowed mode).

Target is Slate Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Screen Position |  |
| boolean | Include Window Position |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Absolute Coordinate |  |

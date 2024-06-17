---
title: Local to Viewport
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface) > [Geometry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface/Geometry)

Translates local coordinate of the geometry provided into local viewport coordinates.

Target is Slate Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Geometry |  |
| vector2d struct | Local Coordinate |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Pixel Position | The position in the game's viewport, usable for line traces and other uses where you need a coordinate in the space of viewport resolution units. |
| vector2d struct | Viewport Position | The position in the space of other widgets in the viewport. Like if you wanted to add another widget to the viewport at the same position in viewport space as this location, this is what you would use. |

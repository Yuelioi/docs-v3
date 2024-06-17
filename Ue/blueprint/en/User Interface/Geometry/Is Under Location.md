---
title: Is Under Location
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface) > [Geometry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface/Geometry)

Absolute coordinates could be either desktop or window space depending on what space the root of the widget hierarchy is in.

Target is Slate Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Geometry |  |
| vector2d struct | Absolute Coordinate |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | true if the provided location in absolute coordinates is within the bounds of this geometry. |

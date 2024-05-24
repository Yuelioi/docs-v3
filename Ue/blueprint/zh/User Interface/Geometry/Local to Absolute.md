---
display_name: Local to Absolute
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface) > [Geometry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface/Geometry)

Translates local coordinates into absolute coordinates

Absolute coordinates could be either desktop or window space depending on what space the root of the widget hierarchy is in.

Target is Slate Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Geometry |  |
| vector2d struct | Local Coordinate |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Return Value | Absolute coordinates |

---
display_name: Is Point in Box with Transform
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Geometry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Geometry)

Determines whether a given point is in a box with a given transform. Includes points on the box.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Point | Point to test |
| transform | Box World Transform | Component-to-World transform of the box. |
| vector | Box Extent | Extents of the box (distance in each axis from origin), in component space. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Whether the point is in the box. |

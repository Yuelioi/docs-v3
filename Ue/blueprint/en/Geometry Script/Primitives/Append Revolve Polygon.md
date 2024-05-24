---
display_name: Append Revolve Polygon
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Primitives](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Primitives)

In the coordinate system of the revolve polygon, +X is towards the "outside" of the revolve donut, and +Y is "up" (ie +Z in local space)
Polygon should be oriented counter-clockwise to produce a correctly-oriented shape, otherwise it will be inside-out
Polygon endpoint is not repeated.

Target is Geometry Script Library Mesh Primitive Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Primitive Options |  |
| transform | Transform |  |
| vector2d struct | Polygon Vertices |  |
| struct | Revolve Options |  |
| real | Radius |  |
| integer | Steps |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | In the coordinate system of the revolve polygon, +X is towards the "outside" of the revolve donut, and +Y is "up" (ie +Z in local space)Polygon should be oriented counter-clockwise to produce a correctly-oriented shape, otherwise it will be inside-outPolygon endpoint is not repeated. |

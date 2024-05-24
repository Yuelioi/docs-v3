---
display_name: Set Polygon Vertex
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Simple Polygon](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/SimplePolygon)

Set the specified vertex of a Simple Polygon. VertexIndex loops around, so e.g., -1 gives the last vertex in the polygon.
Does nothing if Polygon has no vertices.

Target is Geometry Script Library Simple Polygon Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Polygon |  |
| integer | Vertex Index |  |
| vector2d struct | Position |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Polygon Is Empty |  |

---
title: Get Polygon Vertex
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Simple Polygon](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/SimplePolygon)

Returns the specified vertex of a Simple Polygon. VertexIndex loops around, so e.g., -1 gives the last vertex in the polygon.
If Polygon has no vertices, returns the zero vector.

Target is Geometry Script Library Simple Polygon Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Polygon |  |
| integer | Vertex Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Polygon Is Empty |  |
| vector2d struct | Return Value | Returns the specified vertex of a Simple Polygon. VertexIndex loops around, so e.g., -1 gives the last vertex in the polygon.If Polygon has no vertices, returns the zero vector. |

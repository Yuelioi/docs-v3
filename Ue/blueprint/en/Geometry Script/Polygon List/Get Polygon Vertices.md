---
title: Get Polygon Vertices
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Polygon List](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolygonList)

Returns the vertices of a Polygon -- either of the outer polygon, if HoleIndex is -1, or specified inner hole.
OutVertices will be empty for invalid Polygon or Hole indices.

Target is Geometry Script Library Polygon List Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Polygon List |  |
| integer | Polygon Index |  |
| integer | Hole Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector2d struct | Out Vertices |  |
| boolean | Valid Indices |  |

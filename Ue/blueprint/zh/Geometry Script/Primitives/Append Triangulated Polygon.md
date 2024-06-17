---
title: Append Triangulated Polygon
order: 26
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Primitives](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Primitives)

Appends a Triangulated Polygon to the Target Mesh.
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
| boolean | Allow Self Intersections |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Appends a Triangulated Polygon to the Target Mesh.Polygon should be oriented counter-clockwise to produce a correctly-oriented shape, otherwise it will be inside-outPolygon endpoint is not repeated. |

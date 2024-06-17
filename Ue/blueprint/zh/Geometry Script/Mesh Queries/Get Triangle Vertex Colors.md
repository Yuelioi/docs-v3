---
title: Get Triangle Vertex Colors
order: 38
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

For the specified TriangleID of the TargetMesh, get the Vertex Colors at each vertex of the Triangle.
These Colors will be taken from the Vertex Color Attribute, ie they will potentially be split-colors.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Triangle ID |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| linearcolor | Color 1 |  |
| linearcolor | Color 2 |  |
| linearcolor | Color 3 |  |
| boolean | Tri Has Valid Vertex Colors | will be returned true if TriangleID exists in TargetMesh and has Vertex Colors set |
| object | Target Mesh |  |

---
title: Get Triangle Normals
order: 35
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

For the specified TriangleID of the Target Mesh, get the Normal vectors at each vertex of the Triangle.
These Normals will be taken from the Normal Overlay, i.e. they will potentially be split-normals.

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
| vector | Normal 1 |  |
| vector | Normal 2 |  |
| vector | Normal 3 |  |
| boolean | Tri Has Valid Normals | will be returned true if TriangleID exists in TargetMesh and has Normals set. |
| object | Target Mesh |  |

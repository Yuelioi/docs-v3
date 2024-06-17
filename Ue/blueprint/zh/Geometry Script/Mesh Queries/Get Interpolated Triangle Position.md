---
title: Get Interpolated Triangle Position
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Compute the interpolated Position (A*Vertex1 + B*Vertex2 + C\*Vertex3), where (A,B,C)=BarycentricCoords and the Vertex positions are taken
from the specified TriangleID of the TargetMesh.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Triangle ID |  |
| vector | Barycentric Coords |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Triangle | will be returned true if TriangleID exists in TargetMesh, and otherwise will be returned false |
| vector | Interpolated Position |  |
| object | Target Mesh |  |

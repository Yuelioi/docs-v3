---
title: Get Interpolated Triangle Normal
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Compute the interpolated Normal (A*Normal1 + B*Normal2 + C\*Normal3), where (A,B,C)=BarycentricCoords and the Normals are taken
from the specified TriangleID in the Normal layer of the TargetMesh.

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
| boolean | Tri Has Valid Normals | will be returned true if TriangleID exists in TargetMesh and has Normals set, and otherwise will be returned false. |
| vector | Interpolated Normal |  |
| object | Target Mesh |  |

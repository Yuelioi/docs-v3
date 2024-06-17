---
title: Get Shortest Surface Path
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Geodesic](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshGeodesic)

Computes a PolyPath that represents the shortest mesh surface path between two prescribed points on the provided mesh.
This can fail if the Start and End points are within separate connected components of the mesh.

Target is Geometry Script Library Mesh Geodesic Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh | defines the surface where the path is computed. |
| integer | Start Triangle ID | the ID of mesh Triangle that contains the start point of the path. |
| vector | Start Bary Coords | indicates the location of start point within the start triangle, in terms of barycentric coordinates. |
| integer | End Triangle ID | the ID of mesh Triangle that contains the end point of the path. |
| vector | End Bary Coords | indicates the location of the end point within the end triangle, in terms of barycentric coordinates. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Shortest Path |  |
| boolean | Found Errors |  |
| object | Target Mesh |  |

---
title: Get Shortest Vertex Path
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Geodesic](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshGeodesic)

Computes a vertex list that represents the shortest path constrained to travel along mesh triangle edges between the prescribed start and end vertex.
This can fail if the Start and End points are within separate connected components of the mesh.

Target is Geometry Script Library Mesh Geodesic Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh | defines the surface where the path is computed. |
| integer | Start Vertex ID | indicates ID of mesh vertex that defines the starting point of the path. |
| integer | End Vertex ID | indicates ID of the mesh vertex that defined the end point of the path. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Vertex IDList |  |
| boolean | Found Errors | will be false on success. |
| object | Target Mesh |  |

---
title: Get Is Dense Mesh
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Returns true if the mesh is dense. For example, no gaps in Vertex IDs or Triangle IDs.
Note if a mesh is not dense, the Compact Mesh node can be used to removed the gaps.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Mesh |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true if the mesh is dense. For example, no gaps in Vertex IDs or Triangle IDs.Note if a mesh is not dense, the Compact Mesh node can be used to removed the gaps. |

---
title: Append Buffers to Mesh
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Edits](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshEdits)

Adds a set of vertices/triangles to the mesh, with Normals, UVs, and Colors; returning the new triangles indices

Target is Geometry Script Library Mesh Basic Edit Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Buffers |  |
| integer | Material ID |  |
| boolean | Defer Change Notifications |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | New Triangle Indices List |  |
| object | Target Mesh | Adds a set of vertices/triangles to the mesh, with Normals, UVs, and Colors; returning the new triangles indices |

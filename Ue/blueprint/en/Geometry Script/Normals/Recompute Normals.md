---
title: Recompute Normals
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Recompute the normals of TargetMesh using the given CalculateOptions. This method will preserve any existing hard
edges, ie each shared triangle-vertex normal is recomputed by averaging the face normals of triangles that reference
that shared triangle-vertex normal

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Calculate Options |  |
| boolean | Defer Change Notifications |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Recompute the normals of TargetMesh using the given CalculateOptions. This method will preserve any existing hardedges, ie each shared triangle-vertex normal is recomputed by averaging the face normals of triangles that referencethat shared triangle-vertex normal |

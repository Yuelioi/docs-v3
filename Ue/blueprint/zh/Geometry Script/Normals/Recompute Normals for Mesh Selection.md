---
title: Recompute Normals for Mesh Selection
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Recompute the normals of TargetMesh on all the triangles/vertices of the given Selection using the given CalculateOptions.
This method will preserve any existing hard edges, ie each shared triangle-vertex normal is recomputed by averaging
the face normals of triangles that reference that shared triangle-vertex normal

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Selection |  |
| struct | Calculate Options |  |
| boolean | Defer Change Notifications |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Recompute the normals of TargetMesh on all the triangles/vertices of the given Selection using the given CalculateOptions.This method will preserve any existing hard edges, ie each shared triangle-vertex normal is recomputed by averagingthe face normals of triangles that reference that shared triangle-vertex normal |

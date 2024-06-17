---
title: Split Mesh by Components
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Decomposition](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Decomposition)

Create a new Mesh for each Connected Component of TargetMesh.
New meshes are drawn from MeshPool if it is provided, otherwise new UDynamicMesh instances are allocated

Target is Geometry Script Library Mesh Decomposition Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | Mesh Pool | New meshes in ComponentMeshes output list are allocated from this pool if it is provided (highly recommended!!) |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Component Meshes | New List of meshes is returned here |
| object | Target Mesh |  |

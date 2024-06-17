---
title: Split Mesh by Polygroups
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Decomposition](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Decomposition)

Create a new Mesh for each Polygroup of TargetMesh. Note that this may be a *large* number of meshes!
New meshes are drawn from MeshPool if it is provided, otherwise new UDynamicMesh instances are allocated

Target is Geometry Script Library Mesh Decomposition Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Group Layer |  |
| object | Mesh Pool | New meshes in ComponentMeshes output list are allocated from this pool if it is provided (highly recommended!!) |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Component Meshes | New List of meshes is returned here |
| integer | Component Polygroups | Original Polygroup for each Mesh in ComponentMeshes is returned here |
| object | Target Mesh |  |

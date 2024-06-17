---
title: Copy Mesh to Skeletal Mesh
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Skeletal Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/SkeletalMesh)

Updates a Skeletal Mesh Asset with new geometry and bone weights data from a Dynamic Mesh.

Target is Geometry Script Library Static Mesh Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | From Dynamic Mesh |  |
| object | To Skeletal Mesh Asset |  |
| struct | Options |  |
| struct | Target LOD |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Failure |  |
| exec | Success |  |
| object | Dynamic Mesh | Updates a Skeletal Mesh Asset with new geometry and bone weights data from a Dynamic Mesh. |

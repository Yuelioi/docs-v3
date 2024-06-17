---
title: Copy Mesh to Static Mesh
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/StaticMesh)

Updates a Static Mesh Asset with new geometry converted from a Dynamic Mesh.

Target is Geometry Script Library Static Mesh Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | From Dynamic Mesh |  |
| object | To Static Mesh Asset |  |
| struct | Options |  |
| struct | Target LOD |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Failure |  |
| exec | Success |  |
| object | Dynamic Mesh | Updates a Static Mesh Asset with new geometry converted from a Dynamic Mesh. |

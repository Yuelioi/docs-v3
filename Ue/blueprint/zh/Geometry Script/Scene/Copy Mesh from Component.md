---
title: Copy Mesh from Component
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Scene](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Scene)

Copy the mesh from a given Component to a Dynamic Mesh.
StaticMeshComponent, DynamicMeshCompnent, and BrushComponent are supported.
This function offers minimal control over the copying, if more control is needed for Static Meshes, use CopyMeshFromStaticMesh.

Target is Geometry Script Library Scene Utility Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Component |  |
| object | To Dynamic Mesh |  |
| struct | Options |  |
| boolean | Transform to World | if true, output mesh is in World space |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Failure |  |
| exec | Success |  |
| transform | Local to World | local-to-world transform is returned here (whether mesh is in local or world space) |
| object | Dynamic Mesh |  |

---
title: Apply Uniform Remesh
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Simplification](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Simplification)

Apply Uniform Remeshing to the TargetMesh.
@warning this function can be quite expensive. The results may be non-deterministic, and are expected to change in future versions.

Target is Geometry Script Library Remeshing Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Remesh Options |  |
| struct | Uniform Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Apply Uniform Remeshing to the TargetMesh.@warning this function can be quite expensive. The results may be non-deterministic, and are expected to change in future versions. |

---
title: Is BVHValid for Mesh
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Spatial](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Spatial)

Checks if the provided Bounding Volume Hierarchy (BVH) can still be used with the Mesh ? it generally returns false if the mesh has been changed.

Target is Geometry Script Library Mesh Spatial

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Test BVH |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid |  |
| object | Target Mesh | Checks if the provided Bounding Volume Hierarchy (BVH) can still be used with the Mesh ? it generally returns false if the mesh has been changed. |

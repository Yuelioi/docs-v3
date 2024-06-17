---
title: Is Point Inside Mesh
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Spatial](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Spatial)

Tests if a point is inside the mesh using the Fast Winding Number query and data stored in the BVH.

Target is Geometry Script Library Mesh Spatial

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Query BVH | is an acceleration structure previously built with this mesh. |
| vector | Query Point | the point in the mesh's 3D local space. |
| struct | Options | control the fast winding number threshold |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Inside |  |
| exec | Outside |  |
| boolean | Is Inside |  |
| object | Target Mesh |  |

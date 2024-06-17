---
title: Find Nearest Point on Mesh
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Spatial](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Spatial)

Finds the nearest point (Nearest Result) on the Target Mesh to a given 3D point (Query Point) by using the Query BVH.

Target is Geometry Script Library Mesh Spatial

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Query BVH | a BVH associated with the Target Mesh |
| vector | Query Point | a 3D location relative to the local space of the mesh |
| struct | Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Found |  |
| exec | Not Found |  |
| struct | Nearest Result | on return, holds the nearest point on the mesh to the QueryPoint |
| object | Target Mesh |  |

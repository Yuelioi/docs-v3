---
title: Find Nearest Ray Intersection with Mesh
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Spatial](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Spatial)

Finds the nearest intersection of a 3D ray with the mesh by using the Query BVH.
Note, depending on the Ray Origin and Ray Direction, there is the possibility that the ray might not intersect with the Target Mesh.
Should the ray miss, the HitResult.bHit will be false and the Outcome will be Not Found.

Target is Geometry Script Library Mesh Spatial

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Query BVH |  |
| vector | Ray Origin |  |
| vector | Ray Direction |  |
| struct | Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Found |  |
| exec | Not Found |  |
| struct | Hit Result |  |
| object | Target Mesh | Finds the nearest intersection of a 3D ray with the mesh by using the Query BVH.Note, depending on the Ray Origin and Ray Direction, there is the possibility that the ray might not intersect with the Target Mesh.Should the ray miss, the HitResult.bHit will be false and the Outcome will be Not Found. |

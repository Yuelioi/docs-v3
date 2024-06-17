---
title: Set Mesh To Facet Normals
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Normals](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Normals)

Recompute the normals of TargetMesh by setting the normals of each triangle vertex to the triangle/face normal.
Each vertex will have a unique normal in each triangle, ie there will be hard edges / split normals at every mesh edge

Target is Geometry Script Library Mesh Normals Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Recompute the normals of TargetMesh by setting the normals of each triangle vertex to the triangle/face normal.Each vertex will have a unique normal in each triangle, ie there will be hard edges / split normals at every mesh edge |

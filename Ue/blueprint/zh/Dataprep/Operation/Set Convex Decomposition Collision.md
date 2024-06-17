---
title: Set Convex Decomposition Collision
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dataprep](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep) > [Operation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep/Operation)

Add complex collision on the static meshes contained in the input array
by the actors contained in the input array

Target is Dataprep Operations Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Selected Objects |  |
| integer | Hull Count | Maximum number of convex pieces that will be created. Must be positive. |
| integer | Max Hull Verts | Maximum number of vertices allowed for any generated convex hull. |
| integer | Hull Precision | Number of voxels to use when generating collision. Must be positive. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Modified Objects |  |

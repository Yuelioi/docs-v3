---
title: Force Nav Mesh Update
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mesh Reconstruction](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MeshReconstruction)

Force navmesh generation to run using the current collision data. This will run even if the collision data has not been udpated! Unless you are changing navmesh settings or similar RequestNavMeshUpdate is reccomended.

Target is MRMesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

---
title: Get Section Material List from Static Mesh
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/StaticMesh)

Extracts the Material List and corresponding Material Indices from the specified LOD of the Static Mesh Asset.
The MaterialList is sorted by Section, so if CopyMeshToStaticMesh was used to create a DynamicMesh, then the returned
MaterialList here will correspond to the MaterialIDs in that DynamicMesh (as each Static Mesh Section becomes a MaterialID, in-order).
So, the returned MaterialList can be passed directly to (eg) a DynamicMeshComponent.

Target is Geometry Script Library Static Mesh Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | From Static Mesh Asset |  |
| struct | Requested LOD |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Failure |  |
| exec | Success |  |
| object | Material List |  |
| integer | Material Index | this returned array is the same size as MaterialList, with each value the index of that Material in the StaticMesh Material List |
| name | Material Slot Names |  |

---
display_name: Check Static Mesh Has Available LOD
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Static Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/StaticMesh)

Check if a Static Mesh Asset has the RequestedLOD available, ie if CopyMeshFromStaticMesh will be able to
succeed for the given LODType and LODIndex.

Target is Geometry Script Library Static Mesh Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Static Mesh Asset |  |
| struct | Requested LOD |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Found |  |
| exec | Not Found |  |
| boolean | Return Value | Check if a Static Mesh Asset has the RequestedLOD available, ie if CopyMeshFromStaticMesh will be able tosucceed for the given LODType and LODIndex. |

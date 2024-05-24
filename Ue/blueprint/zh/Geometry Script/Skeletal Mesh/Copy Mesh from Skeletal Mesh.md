---
display_name: Copy Mesh from Skeletal Mesh
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Skeletal Mesh](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/SkeletalMesh)

Extracts a Dynamic Mesh from a Skeletal Mesh Asset.

Target is Geometry Script Library Static Mesh Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | From Skeletal Mesh Asset |  |
| object | To Dynamic Mesh |  |
| struct | Asset Options |  |
| struct | Requested LOD |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Failure |  |
| exec | Success |  |
| object | Dynamic Mesh | Extracts a Dynamic Mesh from a Skeletal Mesh Asset. |

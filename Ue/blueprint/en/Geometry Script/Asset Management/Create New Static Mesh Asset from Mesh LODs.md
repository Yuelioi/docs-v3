---
display_name: Create New Static Mesh Asset from Mesh LODs
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Asset Management](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/AssetManagement)

Create a new StaticMesh asset from a collection of LODs represented by an array of DynamicMeshes.
Save the asset at the AssetPathAndName location.

Target is Geometry Script Library Create New Asset Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | From Dynamic Mesh |  |
| string | Asset Path and Name |  |
| struct | Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Failure |  |
| exec | Success |  |
| object | Static Mesh Asset | Create a new StaticMesh asset from a collection of LODs represented by an array of DynamicMeshes.Save the asset at the AssetPathAndName location. |

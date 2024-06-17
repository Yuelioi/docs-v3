---
title: Create New Skeletal Mesh Asset from Mesh LODs
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Asset Management](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/AssetManagement)

Create a new SkeletalMesh asset from a collection of LODs represented by an array of DynamicMeshes and a Skeleton.
Save the asset at the AssetPathAndName location.

Target is Geometry Script Library Create New Asset Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | From Dynamic Mesh LODs |  |
| object | In Skeleton |  |
| string | Asset Path and Name |  |
| struct | Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Failure |  |
| exec | Success |  |
| object | Skeletal Mesh Asset | Create a new SkeletalMesh asset from a collection of LODs represented by an array of DynamicMeshes and a Skeleton.Save the asset at the AssetPathAndName location. |

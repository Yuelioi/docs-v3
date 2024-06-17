---
title: Create New Static Mesh Asset from Mesh
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Asset Management](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/AssetManagement)

Create a new StaticMesh asset from a DynamicMesh. Save the asset at the AssetPathAndName location.

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
| object | Static Mesh Asset | Create a new StaticMesh asset from a DynamicMesh. Save the asset at the AssetPathAndName location. |

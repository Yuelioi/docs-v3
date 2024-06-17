---
title: Get Material IDs Of Triangles
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Materials)

This populates the MaterialIDList with Material IDs for each triangle in the TriangleIDList.
If a triangle is not present in the Target Mesh the number -1 will be used for the corresponding Material ID.
If Material IDs are not enabled on the TargetMesh no Material IDs will be added to the result list.

Target is Geometry Script Library Mesh Material Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Mesh |  |
| struct | Triangle IDList |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Material IDList |  |
| object | Target Mesh | This populates the MaterialIDList with Material IDs for each triangle in the TriangleIDList.If a triangle is not present in the Target Mesh the number -1 will be used for the corresponding Material ID.If Material IDs are not enabled on the TargetMesh no Material IDs will be added to the result list. |

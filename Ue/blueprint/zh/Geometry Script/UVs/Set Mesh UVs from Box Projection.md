---
title: Set Mesh UVs from Box Projection
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Using Box Projection, update the UVs in the UV Channel for an entire mesh or a subset defined by a non-empty Selection.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| transform | Box Transform |  |
| struct | Selection |  |
| integer | Min Island Tri Count |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Using Box Projection, update the UVs in the UV Channel for an entire mesh or a subset defined by a non-empty Selection. |

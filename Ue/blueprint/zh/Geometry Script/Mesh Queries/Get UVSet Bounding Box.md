---
title: Get UVSet Bounding Box
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshQueries)

Gets the 2D bounding box of all UVs in the UV Channel. If the UV Channel does not exist, or if the UV Channel is empty, the resulting box will be invalid.

Target is Geometry Script Library Mesh Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Mesh |  |
| integer | UV Channel |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Valid UV Channel |  |
| boolean | UV Channel Is Empty |  |
| struct | Bounding Box | Gets the 2D bounding box of all UVs in the UV Channel. If the UV Channel does not exist, or if the UV Channel is empty, the resulting box will be invalid. |

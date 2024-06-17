---
title: Apply Bend Warp to Mesh
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Deformations](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Deformations)

Applies a Bend Warp around an axis defined by the Bend Orientation transform.
The extents of the affected region can be controlled by the Options.

Target is Geometry Script Library Mesh Deform Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Options |  |
| transform | Bend Orientation |  |
| real | Bend Angle |  |
| real | Bend Extent |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Applies a Bend Warp around an axis defined by the Bend Orientation transform.The extents of the affected region can be controlled by the Options. |

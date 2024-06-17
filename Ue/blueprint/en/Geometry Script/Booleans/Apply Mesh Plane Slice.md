---
title: Apply Mesh Plane Slice
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Booleans](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Booleans)

Slices a mesh into two halves, with optional hole filling.

Target is Geometry Script Library Mesh Boolean Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh | Dynamic Mesh to be updated by the slice. |
| transform | Cut Frame | defines the plane used to slice the TargetMesh. |
| struct | Options | selects additional clean-up operations performed after the cut. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |

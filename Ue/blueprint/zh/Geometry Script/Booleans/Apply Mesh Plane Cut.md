---
title: Apply Mesh Plane Cut
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Booleans](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Booleans)

Applies a plane cut to a mesh, optionally filling any holes created.

Target is Geometry Script Library Mesh Boolean Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh | Dynamic Mesh to updated with the cut |
| transform | Cut Frame | defines the plane used to cut the TargetMesh |
| struct | Options | selects additional clean-up operations performed after the cut. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |

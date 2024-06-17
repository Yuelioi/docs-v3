---
title: Combine Mesh Selections
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Combine two Mesh Selections into a new Mesh Selection.
The two inputs SelectionA and SelectionB must have the same Type.

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Selection A |  |
| struct | Selection B |  |
| enum | Combine Mode | specifies how the selection elements in SelectionA and SelectionB are interpreted/combined. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Result Selection |  |

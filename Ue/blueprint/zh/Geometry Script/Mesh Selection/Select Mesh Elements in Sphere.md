---
title: Select Mesh Elements in Sphere
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Create a new Mesh Selection of the SelectionType for the TargetMesh by finding all elements contained in the Sphere.

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| vector | Sphere Origin | center point of the Sphere |
| real | Sphere Radius | radius of the Sphere |
| enum | Selection Type |  |
| boolean | Invert | return a selection of all elements not in the Sphere |
| integer | Min Num Triangle Points | number of vertices of a triangle that must be in the Sphere for it to be selected (1,2, or 3) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Selection |  |
| object | Target Mesh |  |

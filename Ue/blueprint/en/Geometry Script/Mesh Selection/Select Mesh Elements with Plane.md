---
title: Select Mesh Elements with Plane
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Create a new Mesh Selection of the SelectionType for the TargetMesh by finding all elements on the "positive" side of a Plane

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| vector | Plane Origin | center point of the Plane |
| vector | Plane Normal | normal vector for the Plane |
| enum | Selection Type |  |
| boolean | Invert | return a selection of all elements on the other (negative) side of the Plane |
| integer | Min Num Triangle Points | number of vertices of a triangle that must be on the positive Plane side to be selected (1,2, or 3) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Selection |  |
| object | Target Mesh |  |

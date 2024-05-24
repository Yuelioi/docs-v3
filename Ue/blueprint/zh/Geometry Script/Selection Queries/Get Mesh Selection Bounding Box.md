---
display_name: Get Mesh Selection Bounding Box
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Selection Queries](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/SelectionQueries)

Get the 3D Bounding Box of a Mesh Selection, ie bounding box of vertices contained in the Selection

Target is Geometry Script Library Mesh Selection Query Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Selection |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Selection Bounds |  |
| boolean | Is Empty | will return as true if the selection was empty (the box will be initialized to 0 in this case) |
| object | Target Mesh |  |

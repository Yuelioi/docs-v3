---
display_name: Set Material IDOn Triangles
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Materials)

Assigns the Material ID to all the triangles specified by the Triangle ID List.

Target is Geometry Script Library Mesh Material Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Triangle IDList | the triangles in the target mesh that will be updated with the new Material ID |
| integer | Material ID | the ID to be assigned to each triangle in the input list. |
| boolean | Defer Change Notifications | if true, the UDynamicMesh does not emit a change event/signal for this modification. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |

---
display_name: Delete Triangles by Material ID
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Materials)

Delete all triangles in TargetMesh with the given MaterialID

Target is Geometry Script Library Mesh Material Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Material ID |  |
| boolean | Defer Change Notifications |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Num Deleted | number of deleted triangles is returned here |
| object | Target Mesh |  |

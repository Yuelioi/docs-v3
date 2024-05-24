---
display_name: GetMaterialIDOfTriangle
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Materials)

Returns the current Material ID for a Triangle.
If the mesh does not have Material IDs enabled or if the Triangle ID is not an element of the mesh, the value 0 will be returned and bIsValidTriangle will be false.

Target is Geometry Script Library Mesh Material Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Mesh |  |
| integer | Triangle ID |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Valid Triangle |  |
| integer | Material ID | Returns the current Material ID for a Triangle.If the mesh does not have Material IDs enabled or if the Triangle ID is not an element of the mesh, the value 0 will be returned and bIsValidTriangle will be false. |

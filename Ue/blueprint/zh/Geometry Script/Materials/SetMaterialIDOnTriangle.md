---
display_name: SetMaterialIDOnTriangle
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Materials)

Assigns the specified triangle the given Material ID.
If the Target Mesh does not have Material IDs enabled, or if the Triangle ID is not an element of the Target Mesh then bIsValidTriangle will be set to false.

Target is Geometry Script Library Mesh Material Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Triangle ID |  |
| integer | Material ID |  |
| boolean | Defer Change Notifications |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Triangle |  |
| object | Target Mesh | Assigns the specified triangle the given Material ID.If the Target Mesh does not have Material IDs enabled, or if the Triangle ID is not an element of the Target Mesh then bIsValidTriangle will be set to false. |

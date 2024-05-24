---
display_name: ConvertUVIslandsToPolyGroups
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Poly Groups](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/PolyGroups)

Creates and assigns a new PolyGroup for each disconnected UV island of a Mesh.
Note, this will have no effect if either the requested UV Layer or Group Layer does not exist.

Target is Geometry Script Library Mesh Polygroup Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Group Layer | indicates PolyGroup Layer that will be populated with unique values for each UV island. |
| integer | UVLayer | specifies the UV Layer used to construct the PolyGroups. |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |

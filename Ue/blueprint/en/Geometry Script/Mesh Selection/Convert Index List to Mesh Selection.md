---
display_name: Convert Index List to Mesh Selection
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Create a Mesh Selection from the Index List. For cases where the IndexList Type does not match
the SelectionType, ConvertMeshSelection with bAllowPartialInclusion=true is used to convert.

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Index List |  |
| enum | Selection Type | type of indices desired in the Output selection |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Selection |  |
| object | Target Mesh |  |

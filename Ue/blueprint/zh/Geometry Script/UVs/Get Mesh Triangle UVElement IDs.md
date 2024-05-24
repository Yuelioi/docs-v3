---
display_name: Get Mesh Triangle UVElement IDs
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Returns the UV Element IDs associated with the three vertices of the triangle in the specified UV Channel.
If the Triangle does not exist in the mesh or if no UVs are set in the specified UV Channel for the triangle, bHaveValidUVs will be returned as false.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| integer | Triangle ID |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Triangle UVElements |  |
| boolean | Have Valid UVs |  |
| object | Target Mesh | Returns the UV Element IDs associated with the three vertices of the triangle in the specified UV Channel.If the Triangle does not exist in the mesh or if no UVs are set in the specified UV Channel for the triangle, bHaveValidUVs will be returned as false. |

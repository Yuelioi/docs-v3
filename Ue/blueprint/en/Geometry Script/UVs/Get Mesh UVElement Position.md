---
display_name: Get Mesh UVElement Position
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Returns the UV Position for a given UV Element ID in the specified UV Channel.
If the UV Set or Element ID does not exist, bIsValidElementID will be returned as false.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| integer | Element ID |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector2d struct | UVPosition |  |
| boolean | Is Valid Element ID |  |
| object | Target Mesh | Returns the UV Position for a given UV Element ID in the specified UV Channel.If the UV Set or Element ID does not exist, bIsValidElementID will be returned as false. |

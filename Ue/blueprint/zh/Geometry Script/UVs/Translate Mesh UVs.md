---
display_name: Translate Mesh UVs
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Update all selected UV values in the specified UV Channel by adding the Translation value to each.
If the provided Selection is empty, the Translation is applied to the entire UV Channel.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| vector2d struct | Translation |  |
| struct | Selection |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Update all selected UV values in the specified UV Channel by adding the Translation value to each.If the provided Selection is empty, the Translation is applied to the entire UV Channel. |

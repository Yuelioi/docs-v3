---
display_name: Set Mesh UVElement Position
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Sets the UV position of a specific ElementID in the given UV Set/Channel
If the UV Set or Element ID does not exist, bIsValidElementID will be returned as false.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| integer | Element ID |  |
| vector2d struct | New UVPosition |  |
| boolean | Defer Change Notifications |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Element ID |  |
| object | Target Mesh | Sets the UV position of a specific ElementID in the given UV Set/ChannelIf the UV Set or Element ID does not exist, bIsValidElementID will be returned as false. |

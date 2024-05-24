---
display_name: Set UVList Item
order: 46
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [List Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/ListUtils)

Updates the value of the FVector2D stored in the UV List at the specified location.
If the Index is invalid, the operation will fail and bValidIndex will be set to false on return.

Target is Geometry Script Library List Utility Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | UVList |  |
| integer | Index |  |
| vector2d struct | New UV |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Index |  |

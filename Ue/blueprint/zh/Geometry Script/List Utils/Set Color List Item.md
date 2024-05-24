---
display_name: Set Color List Item
order: 43
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [List Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/ListUtils)

Updates the value of the FLinearColor stored in the Color List at the specified location.
If the Index is invalid, the operation will fail and bValidIndex will be set to false.

Target is Geometry Script Library List Utility Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Color List |  |
| integer | Index |  |
| linearcolor | New Color |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Is Valid Index |  |

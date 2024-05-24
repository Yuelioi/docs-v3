---
display_name: Get Color List Item
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [List Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/ListUtils)

Returns the FLinearColor stored in the Color List at the specified location.
If the Index is not valid for this Color List, FLinearColor::White will be returned and bIsValidIndex set to false.

Target is Geometry Script Library List Utility Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Color List |  |
| integer | Index |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Is Valid Index |  |
| linearcolor | Return Value | Returns the FLinearColor stored in the Color List at the specified location.If the Index is not valid for this Color List, FLinearColor::White will be returned and bIsValidIndex set to false. |

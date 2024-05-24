---
display_name: Remap Material IDs
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Materials)

For all triangles with a Material ID matching the given value (From Material ID), update the Material ID to the new value (To Material ID).

Target is Geometry Script Library Mesh Material Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | From Material ID |  |
| integer | To Material ID |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | For all triangles with a Material ID matching the given value (From Material ID), update the Material ID to the new value (To Material ID). |

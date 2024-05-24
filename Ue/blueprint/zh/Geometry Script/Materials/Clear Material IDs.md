---
display_name: Clear Material IDs
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Materials](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Materials)

Resets all Material IDs on a mesh to the given ClearValue, or 0 if no ClearValue is provided.
If Material IDs are not already enabled on the Target Mesh, this function will first enable them and then set the value.

Target is Geometry Script Library Mesh Material Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | Clear Value |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Resets all Material IDs on a mesh to the given ClearValue, or 0 if no ClearValue is provided.If Material IDs are not already enabled on the Target Mesh, this function will first enable them and then set the value. |

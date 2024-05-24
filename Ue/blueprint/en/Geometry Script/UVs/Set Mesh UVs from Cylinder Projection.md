---
display_name: Set Mesh UVs from Cylinder Projection
order: 19
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Using Cylinder Projection, update the UVs in the UV Channel for an entire mesh or a subset defined by a non-empty Selection.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| transform | Cylinder Transform |  |
| struct | Selection |  |
| real | Split Angle |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Using Cylinder Projection, update the UVs in the UV Channel for an entire mesh or a subset defined by a non-empty Selection. |

---
display_name: Repack Mesh UVs
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [UVs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/UVs)

Packs the existing UV islands in the specified UV Channel into standard UV space based on the Repack Options.

Target is Geometry Script Library Mesh UVFunctions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| integer | UV Channel |  |
| struct | Repack Options |  |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh | Packs the existing UV islands in the specified UV Channel into standard UV space based on the Repack Options. |

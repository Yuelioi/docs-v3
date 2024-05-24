---
display_name: Apply Mesh Bevel Selection
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Modeling](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/Modeling)

Apply a Mesh Bevel operation to parts of TargetMesh using the BevelOptions settings.

Target is Geometry Script Library Mesh Modeling Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Selection | specifies which mesh edges to Bevel |
| enum | Bevel Mode | specifies how Selection should be converted to a Triangle Region or set of PolyGroup Edges |
| struct | Bevel Options | settings for the Bevel Operation |
| object | Debug |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Target Mesh |  |

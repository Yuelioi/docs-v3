---
display_name: Invert Mesh Selection
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Invert the Selection on the TargetMesh, ie select what is not currently selected

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Selection |  |
| boolean | Only to Connected | if true, the inverse is limited to mesh areas geometrically connected to the Selection, instead of the entire mesh |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | New Selection |  |
| object | Target Mesh |  |

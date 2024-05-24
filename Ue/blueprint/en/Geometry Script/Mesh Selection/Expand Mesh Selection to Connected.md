---
display_name: Expand Mesh Selection to Connected
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Geometry Script](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript) > [Mesh Selection](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GeometryScript/MeshSelection)

Expand the Selection on the TargetMesh to connected regions and return the NewSelection

Target is Geometry Script Library Mesh Selection Functions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Mesh |  |
| struct | Selection |  |
| enum | Connection Type | defines what "connected" means, ie purely geometric connection, or some additional constraint like same MaterialIDs/etc |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | New Selection |  |
| object | Target Mesh |  |

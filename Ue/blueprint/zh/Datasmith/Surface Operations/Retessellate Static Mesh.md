---
display_name: Retessellate Static Mesh
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith) > [Surface Operations](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith/SurfaceOperations)

Re-tessellate LOD 0 of a static mesh if it contains parametric surface data.

Target is CAD Surface Operations Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Static Mesh | Static mesh to re-tessellate. |
| struct | Tessellation Settings | Tessellation settings to use. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| text | Failure Reason | Text describing the reason of failure. |
| boolean | Return Value | True if successful, false otherwise |

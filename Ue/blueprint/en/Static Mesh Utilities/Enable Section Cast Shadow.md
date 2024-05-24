---
display_name: Enable Section Cast Shadow
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Enables/disables mesh section shadow casting for a specific LOD.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Static mesh to Enables/disables shadow casting from. |
| boolean | Cast Shadow | If the section should cast shadow. |
| integer | LODIndex | Index of the StaticMesh LOD. |
| integer | Section Index | Index of the StaticMesh Section. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

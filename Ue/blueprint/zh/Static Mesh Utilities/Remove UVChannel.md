---
display_name: Remove UVChannel
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Removes the UV channel at the specified channel index on the given LOD of a StaticMesh.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Static mesh on which to remove the UV channel. |
| integer | LODIndex | Index of the StaticMesh LOD. |
| integer | UVChannel Index | Index where to remove the UV channel. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the UV channel was removed. |

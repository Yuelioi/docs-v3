---
display_name: Insert UVChannel
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Inserts an empty UV channel at the specified channel index on the given LOD of a StaticMesh.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Static mesh on which to insert a UV channel. |
| integer | LODIndex | Index of the StaticMesh LOD. |
| integer | UVChannel Index | Index where to insert the UV channel. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if a UV channel was added. |

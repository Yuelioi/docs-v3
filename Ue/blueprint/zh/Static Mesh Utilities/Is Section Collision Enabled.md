---
display_name: Is Section Collision Enabled
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Checks if a specific LOD mesh section has collision.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Static Mesh | Static mesh to remove collisions from. |
| integer | LODIndex | Index of the StaticMesh LOD. |
| integer | Section Index | Index of the StaticMesh Section. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | True if the collision is enabled for the specified LOD of the StaticMesh section. |

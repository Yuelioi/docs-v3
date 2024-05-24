---
display_name: Get Convex Collision Count
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Get number of convex collisions present on a static mesh.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Mesh to query on. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | An integer representing the number of convex collisions on the input static mesh. An negative value indicates that the command could not be executed. See log for explanation. |

---
display_name: Set Lods with Notification
order: 40
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Static Mesh Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/StaticMeshUtilities)

Remove then add LODs on a static mesh.
The static mesh must have at least LOD 0.
The LOD 0 of the static mesh is kept after removal.
The build settings of LOD 0 will be applied to all subsequent LODs.

Target is Static Mesh Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Static Mesh | Mesh to process. |
| struct | Reduction Options | Options on how to generate LODs on the mesh. |
| boolean | Apply Changes | Indicates if change must be notified. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | the number of LODs generated on the input mesh. An negative value indicates that the reduction could not be performed. See log for explanation. No action will be performed if ReductionOptions.ReductionSettings is empty |

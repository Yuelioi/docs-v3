---
display_name: Save Pose Snapshot
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Pose](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Pose)

Takes a snapshot of the current skeletal mesh component pose & saves it internally.
This snapshot can then be retrieved by name in the animation blueprint for blending.
The snapshot is taken at the current LOD, so if for example you took the snapshot at LOD1 and then used it at LOD0 any bones not in LOD1 will use the reference pose

Target is Anim Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Snapshot Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

---
display_name: Get Movement Base Transform
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover/ Movement Bases](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover_MovementBases)

Get the transform (local-to-world) for the given MovementBase, optionally at the location of a bone. Returns false if MovementBase is nullptr, or if BoneName is not a valid bone.

Target is Based Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Movement Base |  |
| name | Bone Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Out Location |  |
| struct | Out Quat |  |
| boolean | Return Value | Get the transform (local-to-world) for the given MovementBase, optionally at the location of a bone. Returns false if MovementBase is nullptr, or if BoneName is not a valid bone. |

---
display_name: Transform Based Location to World
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover/ Movement Bases](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover_MovementBases)

Convert a local location to a world location for a given MovementBase. Returns false if MovementBase is nullptr, or if BoneName is not a valid bone. Scaling is ignored.

Target is Based Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Movement Base |  |
| name | Bone Name |  |
| vector | Local Location |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Out Location World Space |  |
| boolean | Return Value | Convert a local location to a world location for a given MovementBase. Returns false if MovementBase is nullptr, or if BoneName is not a valid bone. Scaling is ignored. |

---
title: Transform World Rotator to Based
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover/ Movement Bases](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover_MovementBases)

Convert a world space rotator to a local rotator for a given MovementBase, optionally relative to the orientation of a bone. Returns false if MovementBase is nullptr, or if BoneName is not a valid bone. Scaling is ignored.

Target is Based Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Movement Base |  |
| name | Bone Name |  |
| rotator | World Space Rotator |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| rotator | Out Local Rotator |  |
| boolean | Return Value | Convert a world space rotator to a local rotator for a given MovementBase, optionally relative to the orientation of a bone. Returns false if MovementBase is nullptr, or if BoneName is not a valid bone. Scaling is ignored. |

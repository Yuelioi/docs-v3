---
display_name: Transform Location to Local
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover/ Movement Bases](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover_MovementBases)

Convert a world location to a local location for a given MovementBase, optionally at the location of a bone. Returns false if MovementBase is nullptr, or if BoneName is not a valid bone. Scaling is ignored.

Target is Based Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Base Pos |  |
| struct | Base Quat |  |
| vector | World Space Location |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Out Local Location |  |

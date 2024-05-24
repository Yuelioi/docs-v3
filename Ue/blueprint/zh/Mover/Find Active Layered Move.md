---
display_name: Find Active Layered Move
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover)

Retrieves an active layered move, by writing to a target instance if it is the matching type. Note: Writing to the struct returned will not modify the active struct.

Target is Mover Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Did Succeed | Flag indicating whether data was actually written to target struct instance |
| wildcard | Out Layered Move | The data struct instance to write to, which must be a FLayeredMoveBase sub-type |

---
display_name: Set Control Sparse Multipliers
order: 99
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Modifies existing control data using the multipliers

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Names | The names of the controls to modify. Note that if you have these in a FPhysicsControlNameArray then it can be split. |
| struct | Control Multiplier | The new control multiplier |
| boolean | Enable Control | Enables the controls if currently disabled |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

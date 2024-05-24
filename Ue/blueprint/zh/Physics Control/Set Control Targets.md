---
display_name: Set Control Targets
order: 115
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Modifies existing control targets - i.e. what they are driving towards, relative to the parent objects

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Names | The names of the controls to modify. Note that if you have these in a FPhysicsControlNameArray then it can be split. |
| struct | Control Target | The new target for the controls |
| boolean | Enable Control | Enables the controls if currently disabled |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

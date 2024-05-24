---
display_name: Set Control Sparse Data
order: 94
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Modifies an existing control data - i.e. the strengths etc of the control driving towards the target

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | The name of the control to update. |
| struct | Control Data | The new control data |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the control was found and modified, false if not |

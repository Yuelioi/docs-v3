---
display_name: Set Control Linear Data
order: 86
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Modifies an existing control's linear data - i.e. the strengths etc of the control driving towards the target

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | The name of the control to modify. |
| real | Strength | The strength used to drive linear motion |
| real | Damping Ratio | The amount of damping associated with the linear strength. 1 Results in critically damped motion |
| real | Extra Damping | The amount of additional linear damping |
| real | Max Force | The maximum force used to drive the linear motion. Zero indicates no limit. |
| boolean | Enable Control | Enables the control if it is currently disabled |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the control was found and modified, false if not |

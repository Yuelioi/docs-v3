---
display_name: Set Control Target
order: 113
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Modifies an existing control target - i.e. what it is driving towards, relative to the parent object

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | The name of the control to modify. |
| struct | Control Target | The new target for the control |
| boolean | Enable Control | Enables the control if it is currently disabled |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the control was found and modified, false if not |

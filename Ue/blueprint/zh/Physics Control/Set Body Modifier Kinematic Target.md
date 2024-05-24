---
display_name: Set Body Modifier Kinematic Target
order: 59
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Sets the kinematic target transform for a body modifier.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | The name of the body modifier to access. |
| vector | Kinematic Target Position | The position to use as the kinematic target of the associated body, if it is kinematic |
| rotator | Kinematic Target Orienation |  |
| boolean | Make Kinematic | If set then the body will be made kinematic. If not set, then it won't be changed. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the body modifier was found, false if not |

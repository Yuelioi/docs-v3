---
display_name: Add Force
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

Add a force to a single rigid body.
This is like a 'thruster'. Good for adding a burst over some (non zero) time. Should be called every frame for the duration of the force.

Target is Physics Thread Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Handle |  |
| vector | Force | Force vector to apply. Magnitude indicates strength of force. |
| boolean | Accel Change | If true, Force is taken as a change in acceleration instead of a physical force (i.e. mass will have no effect). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

---
display_name: Set Body Modifiers Update Kinematic from Simulation
order: 71
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Sets whether body modifiers should update kinematics from the simulation results

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Names | The names of the body modifiers to access. Note that if you have these in a FPhysicsControlNameArray then it can be split. |
| boolean | Update Kinematic from Simulation | Whether the body should be updated from the simulation when it is kinematic, or whether it should track the kinematic target directly. This will be most likely useful when using async physics, in order to make kinematic parts behave the same as dynamic ones. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

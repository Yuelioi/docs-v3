---
display_name: Get Cached Bone Velocity
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Gets the linear velocity of the requested bone that will be used as a target (in world space). Target
velocities for bones that are not found will be set to zero. Note that these targets will have been
calculated and cached at the start of the Physics Control Component, so if using the built in tick,
may be too old to be useful. If you manually update the component then you can access these target
velocities prior to applying your own targets.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Skeletal Mesh Component |  |
| name | Bone Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Return Value | Gets the linear velocity of the requested bone that will be used as a target (in world space). Targetvelocities for bones that are not found will be set to zero. Note that these targets will have beencalculated and cached at the start of the Physics Control Component, so if using the built in tick,may be too old to be useful. If you manually update the component then you can access these targetvelocities prior to applying your own targets. |

---
title: Get Cached Bone Angular Velocities
order: 30
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

Gets the angular velocities of the requested bones that will be used as targets (in world space). Target
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
| name | Bone Names |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Return Value | Gets the angular velocities of the requested bones that will be used as targets (in world space). Targetvelocities for bones that are not found will be set to zero. Note that these targets will have beencalculated and cached at the start of the Physics Control Component, so if using the built in tick,may be too old to be useful. If you manually update the component then you can access these targetvelocities prior to applying your own targets. |

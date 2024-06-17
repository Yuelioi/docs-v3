---
title: Set All Bodies Below Physics Disabled
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

\[WARNING: Chaos Only\]
Set all of the bones below passed in bone to be disabled or not for the associated physics solver
Bodies will not be colliding or be part of the physics simulation.
This is different from SetAllBodiesBelowSimulatePhysics that changes bodies to Kinematic/simulated

Target is Skeletal Mesh Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Bone Name |  |
| boolean | Disabled |  |
| boolean | Include Self |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

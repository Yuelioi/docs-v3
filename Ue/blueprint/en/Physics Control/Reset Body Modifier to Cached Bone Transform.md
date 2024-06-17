---
title: Reset Body Modifier to Cached Bone Transform
order: 50
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

This flags the body associated with the modifier to set (using teleport) its position and velocity to
the cached animation target. This will only affect skeletal mesh component bodies.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name | The name of the body modifier to use to identify the body to reset. |
| enum | Behavior | When the reset should happen. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the body modifier is found (even if no cached target is found), and false otherwise. |

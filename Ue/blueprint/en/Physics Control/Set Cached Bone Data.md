---
title: Set Cached Bone Data
order: 79
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics Control](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PhysicsControl)

This allows the caller to override the target that will have been calculated and cached at the start of
the Physics Control Component update. This is unlikely to be useful when using the built in tick,
but if you are manually updating the component then you may wish to call this after UpdateTargetCaches
but before UpdateControls.

Target is Physics Control Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Skeletal Mesh Component |  |
| name | Bone Name |  |
| transform | TM |  |
| vector | Velocity |  |
| vector | Angular Velocity |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if successful, and false if no cached target can be found for the bone. |

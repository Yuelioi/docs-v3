---
title: Request Slot Group Inertialization
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Inertial Blending](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/InertialBlending)

Requests an inertial blend during the next anim graph update. Requires your anim graph to have a slot node belonging to the specified group name

Target is Anim Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | In Slot Group Name |  |
| real | Duration |  |
| object | Blend Profile |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

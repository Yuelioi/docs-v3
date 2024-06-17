---
title: Deproject Scene Capture to World
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Camera)

Transforms the given 2D UV coordinate into a 3D world-space point and direction.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Scene Capture 2D | Deproject using this scene capture's view. |
| vector2d struct | Target UV |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | World Position | (out) Corresponding 3D position on camera near plane, in world space. |
| vector | World Direction | (out) World space direction vector away from the camera at the given 2d point. |
| boolean | Return Value |  |

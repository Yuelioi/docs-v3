---
title: Start Camera Shake from Source
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Camera Shakes](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CameraShakes)

Plays a camera shake on this camera.

Target is Player Camera Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Shake Class |  |
| object | Source Component | The source from which the camera shake originates. |
| real | Scale | Applies an additional constant scale on top of the dynamic scale computed with the distance to the source |
| enum | Play Space | Which coordinate system to play the shake in (affects oscillations and camera anims) |
| rotator | User Play Space Rot | Coordinate system to play shake when PlaySpace == CAPS_UserDefined. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |

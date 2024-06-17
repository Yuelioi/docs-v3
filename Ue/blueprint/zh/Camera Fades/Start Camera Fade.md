---
title: Start Camera Fade
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Camera Fades](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CameraFades)

Does a camera fade to/from a solid color. Animates automatically.

Target is Player Camera Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | From Alpha | Alpha at which to begin the fade. Range \[0..1\], where 0 is fully transparent and 1 is fully opaque solid color. |
| real | To Alpha | Alpha at which to finish the fade. |
| real | Duration | How long the fade should take, in seconds. |
| linearcolor | Color | Color to fade to/from. |
| boolean | Should Fade Audio | True to fade audio volume along with the alpha of the solid color. |
| boolean | Hold when Finished | True for fade to hold at the ToAlpha until explicitly stopped (e.g. with StopCameraFade) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

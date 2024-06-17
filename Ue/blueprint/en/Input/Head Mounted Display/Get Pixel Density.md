---
title: Get Pixel Density
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [Head Mounted Display](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/HeadMountedDisplay)

Returns the current VR pixel density. Pixel density sets the VR render
target texture size as a factor of recommended texture size. The recommended
texture size is the size that will result in no under sampling in most
distorted area of the view when computing the final image to be displayed
on the device by the runtime compositor.

Target is Head Mounted Display Function Library

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | (float) The pixel density to be used in VR mode. |

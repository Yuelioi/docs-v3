---
title: Create Undistort UVDisplacement Map
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lens Distortion](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LensDistortion) > [Open CV](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LensDistortion/OpenCV)

Creates a texture containing a DisplacementMap in the Red and the Green channel for undistorting a camera image.
This call can take quite some time to process depending on the resolution.

Target is Open CVLens Distortion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Lens Parameters | The Lens distortion parameters with which to compute the UV displacement map. |
| struct | Image Size | The size of the camera image to be undistorted in pixels. Scaled down resolution will have an impact. |
| real | Cropping Factor | One means OpenCV will attempt to crop out all empty pixels resulting from the process (essentially zooming the image). Zero will keep all pixels. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Camera View Info | Information computed by OpenCV about the undistorted space. Can be used with SceneCapture to adjust FOV. |
| object | Return Value | Texture2D containing the distort to undistort space displacement map. |

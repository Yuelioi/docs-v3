---
display_name: Draw Displacement Map to Render Target
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Lens Distortion](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LensDistortion) > [Open CV](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LensDistortion/OpenCV)

Draws UV displacement map within the output render target.

- Red & green channels hold the distort to undistort displacement;
- Blue & alpha channels hold the undistort to distort displacement.

Target is Open CVLens Distortion Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Output Render Target | The render target to draw to. Don't necessarily need to have same resolution or aspect ratio as distorted render. |
| object | Pre Computed Undistort Displacement Map | Distort to undistort displacement pre computed using OpenCV in engine or externally. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

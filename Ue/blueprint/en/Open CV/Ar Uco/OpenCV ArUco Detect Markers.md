---
title: OpenCV ArUco Detect Markers
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Open CV](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/OpenCV) > [Ar Uco](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/OpenCV/ArUco)

Detects all ArUco markers in the supplied image

Target is Open CVBlueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Render Target | Input image in which to search for markers |
| enum | In Dictionary | Which ArUco marker dictionary to use for detection |
| enum | In Dictionary Size | The size of the ArUco marker dictionary |
| boolean | Debug Draw Markers | If true, output a Texture2D showing the detected marker debug info overlaid on the input image |
| boolean | Estimate Pose | If true, return the 3D pose for each marker relative to the camera position |
| real | In Marker Length in Meters | Length in meters of one side of the physical marker (required if bEstimatePose is True) |
| struct | In Lens Distortion Parameters |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Debug Texture | Output debug image (required if bDebugDrawMarkers is True) |
| struct | Out Detected Markers | Output array of markers detected in the input image |
| integer | Return Value | Total number of markers detected in the input image |

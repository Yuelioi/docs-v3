---
title: OpenCV Chessboard Detect Corners
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Open CV](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/OpenCV_1)

Detects a camera calibration chessboard in the supplied image

Target is Open CVBlueprint Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Render Target | Input image in which to search for a chessboard |
| struct | In Pattern Size | Number of interior corners on the physical chessboard (rows, columns) |
| boolean | Debug Draw Corners | If true, output a Texture2D showing the detected corner debug info overlaid on the input image |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Debug Texture | Output debug image (required if bDebugDrawCorners is True) |
| vector2d struct | Out Detected Corners | Output array of corners detected in the input image |
| integer | Return Value | Total number of corners detected in the input image |

---
title: Editor Apply Spline
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Landscape](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Landscape) > [Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Landscape/Editor)

Deform landscape using a given spline

Target is Landscape Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Spline Component | The component containing the spline data |
| real | Start Width | Width of the spline at the start node, in Spline Component local space |
| real | End Width | Width of the spline at the end node, in Spline Component local space |
| real | Start Side Falloff | Width of the falloff at either side of the spline at the start node, in Spline Component local space |
| real | End Side Falloff | Width of the falloff at either side of the spline at the end node, in Spline Component local space |
| real | Start Roll | Roll applied to the spline at the start node, in degrees. 0 is flat |
| real | End Roll | Roll applied to the spline at the end node, in degrees. 0 is flat |
| integer | Num Subdivisions | Number of triangles to place along the spline when applying it to the landscape. Higher numbers give better results, but setting it too high will be slow and may cause artifacts |
| boolean | Raise Heights | Allow the landscape to be raised up to the level of the spline. If both bRaiseHeights and bLowerHeights are false, no height modification of the landscape will be performed |
| boolean | Lower Heights | Allow the landscape to be lowered down to the level of the spline. If both bRaiseHeights and bLowerHeights are false, no height modification of the landscape will be performed |
| object | Paint Layer | LayerInfo to paint, or none to skip painting. The landscape must be configured with the same layer info in one of its layers or this will do nothing! |
| name | Edit Layer Name | Name of the landscape edit layer to affect (in Edit Layers mode) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

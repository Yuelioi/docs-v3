---
title: Get View Projection Matrix
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Camera)

Returns the View Matrix, Projection Matrix and the View x Projection Matrix for a given view

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Desired View | FMinimalViewInfo struct for a camera. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | View Matrix | (out) Corresponding View Matrix |
| struct | Projection Matrix | (out) Corresponding Projection Matrix |
| struct | View Projection Matrix | (out) Corresponding View x Projection Matrix |

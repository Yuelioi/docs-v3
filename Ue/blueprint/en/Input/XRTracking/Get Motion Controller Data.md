---
title: Get Motion Controller Data
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input) > [XRTracking](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Input/XRTracking)

Cross XR-System query that returns critical information about the motion controller (position, orientation, hand/finger position)

Target is Head Mounted Display Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | World Context | Any object in the world (the player pawn would work). Used in PIE to make sure we get this data from a motioncontroller component that is currently active, rather than one in an editor view world that is never tracked. |
| enum | Hand | Indicates which hand we want data for. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Motion Controller Data | \[out\] Struct filled with information about the motion controller state. |

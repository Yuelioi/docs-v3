---
title: Get Max Desired Age Tick Delta
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Niagara)

Get the maximum CPU time in seconds we will simulate to the desired age, when we go beyond this limit ticks will be processed in the next frame.
This is only relevant when using the DesiredAge age update mode.
Note: The componet will not be visibile if we have ticks to process and SetCanRenderWhileSeeking is set to true

Target is Niagara Particle System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Get the maximum CPU time in seconds we will simulate to the desired age, when we go beyond this limit ticks will be processed in the next frame.This is only relevant when using the DesiredAge age update mode.Note: The componet will not be visibile if we have ticks to process and SetCanRenderWhileSeeking is set to true |

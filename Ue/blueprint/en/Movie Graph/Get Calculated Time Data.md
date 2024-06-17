---
title: Get Calculated Time Data
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

TickProducingFrames will be called for a frame (before the frame starts) and then this will be
called at the end of the frame when we kick off the renders for the frame. Should return data
needed to calculate the correct rendering timestep.

Target is Movie Graph Time Step Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | TickProducingFrames will be called for a frame (before the frame starts) and then this will becalled at the end of the frame when we kick off the renders for the frame. Should return dataneeded to calculate the correct rendering timestep. |

---
title: Capture Niagara Sim Cache Multi Frame
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara Sim Cache](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NiagaraSimCache)

Capture multiple frames from the provided simulation into a SimCache until the simulation becomes inactive, completes or we hit the NumFrames limit.
Capture occurs at the end of each frame with the first frame being this frame.
CaptureRate allows you to reduce the rate of capture, i.e. a rate of 2 would capture frames 0, 2, 4, etc.
When AdvanceSimulation is true we will manually advance the simulation in a loop until we have captured the number of frames request, rather than reading from the component each frame.

Target is Async Niagara Capture Sim Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sim Cache |  |
| struct | Create Parameters |  |
| object | Niagara Component |  |
| integer | Num Frames |  |
| integer | Capture Rate |  |
| boolean | Advance Simulation |  |
| real | Advance Delta Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Action |  |
| object | Out Sim Cache |  |
| exec | Capture Complete |  |
| boolean | Success |  |

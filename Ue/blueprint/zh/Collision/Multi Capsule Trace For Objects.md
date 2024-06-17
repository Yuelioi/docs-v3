---
title: Multi Capsule Trace For Objects
order: 51
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Sweeps a capsule along the given line and returns all hits encountered.
This only finds objects that are of a type specified by ObjectTypes.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Start | Start of line segment. |
| vector | End | End of line segment. |
| real | Radius | Radius of the capsule to sweep |
| real | Half Height | Distance from center of capsule to tip of hemisphere endcap. |
| enum | Object Types | Array of Object Types to trace |
| boolean | Trace Complex | True to test against complex collision, false to test against simplified collision. |
| object | Actors to Ignore |  |
| enum | Draw Debug Type |  |
| boolean | Ignore Self |  |
| linearcolor | Trace Color |  |
| linearcolor | Trace Hit Color |  |
| real | Draw Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Hits | A list of hits, sorted along the trace from start to finish. The blocking hit will be the last hit, if there was one. |
| boolean | Return Value | True if there was a hit, false otherwise. |

---
title: Capsule Trace By Channel
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Sweeps a capsule along the given line and returns the first blocking hit encountered.
This trace finds the objects that RESPOND to the given TraceChannel

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Start | Start of line segment. |
| vector | End | End of line segment. |
| real | Radius | Radius of the capsule to sweep |
| real | Half Height | Distance from center of capsule to tip of hemisphere endcap. |
| enum | Trace Channel |  |
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
| struct | Out Hit | Properties of the trace hit. |
| boolean | Return Value | True if there was a hit, false otherwise. |

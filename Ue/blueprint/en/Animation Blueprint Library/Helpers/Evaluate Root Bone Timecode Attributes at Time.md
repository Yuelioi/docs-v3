---
title: Evaluate Root Bone Timecode Attributes at Time
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation Blueprint Library](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimationBlueprintLibrary) > [Helpers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimationBlueprintLibrary/Helpers)

Evaluates timecode attributes (e.g. "TCFrame", "TCSecond", etc.) of the root bone and returns the resulting qualified frame time.

Target is Animation Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Animation Sequence Base |  |
| real | Eval Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Out Qualified Frame Time |  |
| boolean | Return Value | : true if the root bone had timecode attributes that could be evaluated and a qualified frame time was set, or false otherwise. |

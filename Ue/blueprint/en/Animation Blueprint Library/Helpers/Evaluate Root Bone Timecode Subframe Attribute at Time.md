---
display_name: Evaluate Root Bone Timecode Subframe Attribute at Time
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation Blueprint Library](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimationBlueprintLibrary) > [Helpers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimationBlueprintLibrary/Helpers)

Evaluates the subframe timecode attribute (e.g. "TCSubframe") of the root bone and returns the resulting value.

Since the subframe component of FFrameTime is clamped to the range \[0.0, 1.0), it cannot accurately represent the use
case where the timecode metadata represents subframe values as whole numbered subframes instead of as a percentage of a
frame the way the engine does. The subframe component of the FQualifiedFrameTime returned by
EvaluateRootBoneTimecodeAttributesAtTime() may not reflect the authored subframe metadata in that case.

This function allows access to the subframe values that were actually authored in the timecode metadata.

Target is Animation Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Animation Sequence Base |  |
| real | Eval Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Out Subframe |  |
| boolean | Return Value | : true if the root bone had a subframe timecode attribute that could be evaluated and a value was set, or false otherwise. |

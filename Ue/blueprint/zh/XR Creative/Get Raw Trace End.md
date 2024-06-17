---
title: Get Raw Trace End
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [XR Creative](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/XRCreative)

If bScaledByImpact is false, this returns the raw input to the smoothing filter, `TraceMaxLength` units away in the +X direction.
If bScaledByImpact is true, the magnitude is shortened to the length of the blocking hit (if any).

Target is XRCreative Pointer Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| boolean | Scaled by Impact |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | If bScaledByImpact is false, this returns the raw input to the smoothing filter, `TraceMaxLength` units away in the +X direction.If bScaledByImpact is true, the magnitude is shortened to the length of the blocking hit (if any). |

---
title: Get Filtered Trace End
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [XR Creative](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/XRCreative)

If bScaledByImpact is false, this is the smoothed filter output, roughly `TraceMaxLength` units away, roughly in the +X direction.
If bScaledByImpact is true, the magnitude is shortened to match the length of a blocking hit (if any).

Target is XRCreative Pointer Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| boolean | Scaled by Impact |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | If bScaledByImpact is false, this is the smoothed filter output, roughly `TraceMaxLength` units away, roughly in the +X direction.If bScaledByImpact is true, the magnitude is shortened to match the length of a blocking hit (if any). |

---
title: Find Relative Look at Rotation
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Rotator](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Rotator)

Find a local rotation (range of \[-180, 180\]) for an object with StartTransform to point at TargetLocation.
Useful for getting LookAt Azimuth or Pawn Aim Offset.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Start Transform |  |
| vector | Target Location |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| rotator | Return Value | Find a local rotation (range of \[-180, 180\]) for an object with StartTransform to point at TargetLocation.Useful for getting LookAt Azimuth or Pawn Aim Offset. |

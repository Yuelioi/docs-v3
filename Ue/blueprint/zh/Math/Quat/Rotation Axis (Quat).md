---
title: Rotation Axis (Quat)
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Quat](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Quat)

Get the axis of rotation of the Quaternion.
This is the axis around which rotation occurs to transform the canonical coordinate system to the target orientation.
For the identity Quaternion which has no such rotation, FVector(1,0,0) is returned.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Q |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Get the axis of rotation of the Quaternion.This is the axis around which rotation occurs to transform the canonical coordinate system to the target orientation.For the identity Quaternion which has no such rotation, FVector(1,0,0) is returned. |

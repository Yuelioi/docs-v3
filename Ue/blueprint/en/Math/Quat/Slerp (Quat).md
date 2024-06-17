---
title: Slerp (Quat)
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Quat](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Quat)

Spherical interpolation between Quaternions. Result is normalized.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | A | The starting quat we interp from |
| struct | B | The target quat we interp to |
| real | Alpha | The interpolation amount, usually 0 to 1. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Quat after spherical interpolation |

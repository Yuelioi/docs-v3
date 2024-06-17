---
title: SlerpNormals
order: 54
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Vector](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Vector)

Interpolate from normalized vector A to normalized vector B along a spherical path.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Normal A | Start direction of interpolation, must be normalized. |
| vector | Normal B | End target direction of interpolation, must be normalized. |
| real | Alpha | interpolation amount, usually between 0-1 |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Vector after interpolating between A and B along a spherical path. |

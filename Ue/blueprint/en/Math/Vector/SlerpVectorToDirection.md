---
title: SlerpVectorToDirection
order: 55
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Vector](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Vector)

Interpolate from a vector to the direction of another vector along a spherical path.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Vector | Vector we interpolate from |
| vector | Direction | Target direction we interpolate to |
| real | Alpha | interpolation amount, usually between 0-1 |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Vector after interpolating between Vector and Direction along a spherical path. The magnitude will remain the length of the starting vector. |

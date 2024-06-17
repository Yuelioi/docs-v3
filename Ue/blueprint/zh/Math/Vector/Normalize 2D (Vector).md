---
title: Normalize 2D (Vector)
order: 42
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Vector](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Vector)

Gets a normalized unit copy of the 2D components of the vector, ensuring it is safe to do so. Z is set to zero.
Returns zero vector if vector length is too small to normalize.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | A |  |
| real | Tolerance | Minimum squared vector length. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Normalized copy if safe, (0,0,0) otherwise. |

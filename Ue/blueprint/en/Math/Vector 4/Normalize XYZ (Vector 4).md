---
title: Normalize XYZ (Vector 4)
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Vector 4](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Vector4)

Gets a normalized unit copy of the vector, ensuring it is safe to do so based on the length. The W element is ignored and the returned vector has W=0.
Returns zero vector if vector length is too small to safely normalize.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | A |  |
| real | Tolerance | Minimum squared vector length. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | A normalized copy if safe, (0,0,0) otherwise. |

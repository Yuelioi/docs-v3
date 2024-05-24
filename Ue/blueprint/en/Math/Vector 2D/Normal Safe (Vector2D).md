---
display_name: Normal Safe (Vector2D)
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Vector 2D](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Vector2D)

Gets a normalized copy of the vector, checking it is safe to do so based on the length.
Returns zero vector if vector length is too small to safely normalize.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | A |  |
| real | Tolerance | Minimum squared length of vector for normalization. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Return Value | A normalized copy of the vector if safe, (0,0) otherwise. |

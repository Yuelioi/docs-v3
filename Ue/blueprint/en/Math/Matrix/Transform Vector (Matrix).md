---
display_name: Transform Vector (Matrix)
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Matrix](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Matrix)

Transform a direction vector - will not take into account translation part of the FMatrix.
If you want to transform a surface normal (or plane) and correctly account for non-uniform scaling you should use TransformByUsingAdjointT.
(Assumes Matrix represents a transform)

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | M |  |
| vector | V |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Transform a direction vector - will not take into account translation part of the FMatrix.If you want to transform a surface normal (or plane) and correctly account for non-uniform scaling you should use TransformByUsingAdjointT.(Assumes Matrix represents a transform) |

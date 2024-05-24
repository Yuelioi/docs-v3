---
display_name: Inverse Transform Vector (Matrix)
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Matrix](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Matrix)

Transform a direction vector by the inverse of this matrix - will not take into account translation part.
If you want to transform a surface normal (or plane) and correctly account for non-uniform scaling you should use TransformByUsingAdjointT with adjoint of matrix inverse.
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
| vector | Return Value | Transform a direction vector by the inverse of this matrix - will not take into account translation part.If you want to transform a surface normal (or plane) and correctly account for non-uniform scaling you should use TransformByUsingAdjointT with adjoint of matrix inverse.(Assumes Matrix represents a transform) |

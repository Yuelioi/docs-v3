---
display_name: Advance Time by Distance Matching
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Distance Matching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DistanceMatching)

Advance the sequence evaluator forward by distance traveled rather than time. A distance curve is required on the animation that
describes the distance traveled by the root bone in the animation. See UDistanceCurveModifier.

Target is Anim Distance Matching Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Update Context | The update context provided in the anim node function. |
| struct | Sequence Evaluator | The sequence evaluator node to operate on. |
| real | Distance Traveled | The distance traveled by the character since the last animation update. |
| name | Distance Curve Name | Name of the curve we want to match |
| vector2d struct | Play Rate Clamp | A clamp on the effective play rate of the animation after distance matching. Set to (0,0) for no clamping. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value |  |

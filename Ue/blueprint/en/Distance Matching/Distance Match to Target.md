---
display_name: Distance Match to Target
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Distance Matching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DistanceMatching)

Set the time of the sequence evaluator to the point in the animation where the distance curve matches the DistanceToTarget input.
A common use case is to achieve stops without foot sliding by, each frame, selecting the point in the animation that matches the distance the character has remaining until it stops.
Note that because this technique sets the time of the animation by distance remaining, it doesn't respect phase of any previous animation (e.g. from a jog cycle).

Target is Anim Distance Matching Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Sequence Evaluator | The sequence evaluator node to operate on. |
| real | Distance to Target | The distance remaining to a target (e.g. a stop or pivot point). |
| name | Distance Curve Name | Name of the curve we want to match |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value |  |

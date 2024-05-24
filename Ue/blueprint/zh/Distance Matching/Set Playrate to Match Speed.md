---
display_name: Set Playrate to Match Speed
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Distance Matching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DistanceMatching)

Set the play rate of the sequence player so that the speed of the animation matches in-game movement speed.
While distance matching is commonly used for transition animations, cycle animations (walk, jog, etc) typically just adjust their play rate to match
the in-game movement speed.
This function assumes that the animation has a constant speed.

Target is Anim Distance Matching Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Sequence Player | The sequence player node to operate on. |
| real | Speed to Match | The in-game movement speed to match. This is usually the current speed of the movement component. |
| vector2d struct | Play Rate Clamp | A clamp on how much the animation's play rate can change to match the in-game movement speed. Set to (0,0) for no clamping. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value |  |

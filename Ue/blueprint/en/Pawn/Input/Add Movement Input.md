---
title: Add Movement Input
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pawn](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn) > [Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn/Input)

Add movement input along the given world direction vector (usually normalized) scaled by 'ScaleValue'. If ScaleValue \< 0, movement will be in the opposite direction.
Base Pawn classes won't automatically apply movement, it's up to the user to do so in a Tick event. Subclasses such as Character and DefaultPawn automatically handle this input and move.

Target is Pawn

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| vector | World Direction | Direction in world space to apply input |
| real | Scale Value | Scale to apply to input. This can be used for analog input, ie a value of 0.5 applies half the normal value, while -1.0 would reverse the direction. |
| boolean | Force | If true always add the input, ignoring the result of IsMoveInputIgnored(). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

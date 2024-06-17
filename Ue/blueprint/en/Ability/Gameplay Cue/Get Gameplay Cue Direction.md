---
title: Get Gameplay Cue Direction
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Gameplay Cue](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/GameplayCue)

Gets the best normalized effect direction for this gameplay cue. This is useful for effects that require the direction of an enemy attack. Returns true if a valid direction could be calculated.

Target is Ability System Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Actor |  |
| struct | Parameters |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Direction |  |
| boolean | Return Value | Gets the best normalized effect direction for this gameplay cue. This is useful for effects that require the direction of an enemy attack. Returns true if a valid direction could be calculated. |

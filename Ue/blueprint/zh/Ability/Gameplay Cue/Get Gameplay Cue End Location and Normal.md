---
display_name: Get Gameplay Cue End Location and Normal
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Gameplay Cue](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/GameplayCue)

Gets the best end location and normal for this gameplay cue. If there is hit result data, it will return this. Otherwise it will return the target actor's location/rotation. If none of this is available, it will return false.

Target is Ability System Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Actor |  |
| struct | Parameters |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Location |  |
| vector | Normal |  |
| boolean | Return Value | Gets the best end location and normal for this gameplay cue. If there is hit result data, it will return this. Otherwise it will return the target actor's location/rotation. If none of this is available, it will return false. |

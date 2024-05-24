---
display_name: Montage Get Effective Play Rate
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Montage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Montage)

Get scaled PlayRate for Montage. This accounts for RateScale, so it will reflect the actual play rate seen in game.
If Montage reference is NULL, scaled PlayRate for any Active Montage will be returned.
If Montage is not playing, 0 is returned.

Target is Anim Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| object | Montage |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Get scaled PlayRate for Montage. This accounts for RateScale, so it will reflect the actual play rate seen in game.If Montage reference is NULL, scaled PlayRate for any Active Montage will be returned.If Montage is not playing, 0 is returned. |

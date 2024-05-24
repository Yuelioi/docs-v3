---
display_name: Montage Get Play Rate
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Montage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Montage)

Get PlayRate for Montage. This does not account for RateScale, so it may not reflect the actual play rate seen in game (see Montage_GetEffectivePlayRate).
If Montage reference is NULL, PlayRate for any Active Montage will be returned.
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
| real | Return Value | Get PlayRate for Montage. This does not account for RateScale, so it may not reflect the actual play rate seen in game (see Montage_GetEffectivePlayRate).If Montage reference is NULL, PlayRate for any Active Montage will be returned.If Montage is not playing, 0 is returned. |

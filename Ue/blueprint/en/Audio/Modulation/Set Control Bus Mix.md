---
title: Set Control Bus Mix
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Sets a Control Bus Mix with the provided stage data, if the stages
are provided in an active instance proxy of the mix.
Does not update UObject definition of the mix.

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Mix | Mix to update |
| struct | Stages | Stages to set. If stage's bus is not referenced by mix, stage's update request is ignored. |
| real | Fade Time | Fade time to user when interpolating between current value and new values. If negative, falls back to last fade time set on stage. If fade time never set on stage, uses attack time set on stage in mix asset. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

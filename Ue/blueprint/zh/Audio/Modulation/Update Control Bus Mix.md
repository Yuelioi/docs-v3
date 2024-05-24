---
display_name: Update Control Bus Mix
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Commits updates from a UObject definition of a bus mix to active instance in audio thread
(ignored if mix has not been activated).

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Mix | Mix to update |
| real | Fade Time | Fade time to user when interpolating between current value and new values. If negative, falls back to last fade time set on stage. If fade time never set on stage, uses attack time set on stage in mix asset. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

---
display_name: Set Sound Mix Class Override
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Overrides the sound class adjuster in the given sound mix. If the sound class does not exist in the input sound mix,
the sound class adjuster will be added to the list of active sound mix modifiers.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Sound Mix Modifier | The sound mix to modify. |
| object | In Sound Class | The sound class to override (or add) in the sound mix. |
| real | Volume | The volume scale to set the sound class adjuster to. |
| real | Pitch | The pitch scale to set the sound class adjuster to. |
| real | Fade in Time | The interpolation time to use to go from the current sound class adjuster values to the new values. |
| boolean | Apply to Children | Whether or not to apply this override to the sound class' children or to just the specified sound class. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

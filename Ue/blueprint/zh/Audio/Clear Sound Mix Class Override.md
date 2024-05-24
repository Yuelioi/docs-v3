---
display_name: Clear Sound Mix Class Override
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Clears any existing override of the Sound Class Adjuster in the given Sound Mix

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Sound Mix Modifier | The sound mix to modify. |
| object | In Sound Class | The sound class in the sound mix to clear overrides from. |
| real | Fade Out Time | The interpolation time to use to go from the current sound class adjuster override values to the non-override values. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

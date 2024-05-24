---
display_name: Set Global Pitch Modulation
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Sets a global pitch modulation scalar that will apply to all non-UI sounds

- Fire and Forget.
- Not Replicated.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | Pitch Modulation | A pitch modulation value to globally set. |
| real | Time Sec | A time value to linearly interpolate the global modulation pitch over from it's current value. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

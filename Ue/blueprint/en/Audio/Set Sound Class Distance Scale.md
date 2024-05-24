---
display_name: Set Sound Class Distance Scale
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Linearly interpolates the attenuation distance scale value from it's current attenuation distance override value
(1.0f it not overridden) to its new attenuation distance override, over the given amount of time

- Fire and Forget.
- Not Replicated.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sound Class | Sound class to to use to set the attenuation distance scale on. |
| real | Distance Attenuation Scale | A scalar for the attenuation distance used for computing distance attenuation. |
| real | Time Sec | A time value to linearly interpolate from the current distance attenuation scale value to the new value. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

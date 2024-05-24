---
display_name: Play Dialogue 2D
order: 38
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Plays a dialogue directly with no attenuation, perfect for UI.

- Fire and Forget.
- Not Replicated.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Dialogue | dialogue to play |
| struct | Context | context the dialogue is to play in |
| real | Volume Multiplier | A linear scalar multiplied with the volume, in order to make the sound louder or softer. |
| real | Pitch Multiplier | A linear scalar multiplied with the pitch. |
| real | Start Time | How far in to the dialogue to begin playback at |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

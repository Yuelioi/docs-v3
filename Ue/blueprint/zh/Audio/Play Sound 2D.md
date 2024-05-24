---
display_name: Play Sound 2D
order: 40
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Plays a sound directly with no attenuation, perfect for UI sounds.

- Fire and Forget.
- Not Replicated.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sound | Sound to play. |
| real | Volume Multiplier | A linear scalar multiplied with the volume, in order to make the sound louder or softer. |
| real | Pitch Multiplier | A linear scalar multiplied with the pitch. |
| real | Start Time | How far in to the sound to begin playback at |
| object | Concurrency Settings | Override concurrency settings package to play sound with |
| object | Owning Actor | The actor to use as the "owner" for concurrency settings purposes. Allows PlaySound calls to do a concurrency limit per owner. |
| boolean | Is UISound | True if sound is UI related, else false |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

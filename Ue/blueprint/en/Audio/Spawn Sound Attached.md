---
display_name: Spawn Sound Attached
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

This function allows users to create and play Audio Components attached to a specific Scene Component.
Useful for spatialized and/or distance-attenuated sounds that need to follow another object in space.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Sound | sound to play |
| object | Attach to Component |  |
| name | Attach Point Name | Optional named point within the AttachComponent to play the sound at |
| vector | Location | Depending on the value of Location Type this is either a relative offset from the attach component/point or an absolute world position that will be translated to a relative offset |
| rotator | Rotation | Depending on the value of Location Type this is either a relative offset from the attach component/point or an absolute world rotation that will be translated to a relative offset |
| enum | Location Type | Specifies whether Location is a relative offset or an absolute world position |
| boolean | Stop when Attached to Destroyed | Specifies whether the sound should stop playing when the owner of the attach to component is destroyed. |
| real | Volume Multiplier | A linear scalar multiplied with the volume, in order to make the sound louder or softer. |
| real | Pitch Multiplier | A linear scalar multiplied with the pitch. |
| real | Start Time | How far in to the sound to begin playback at |
| object | Attenuation Settings | Override attenuation settings package to play sound with |
| object | Concurrency Settings | Override concurrency settings package to play sound with |
| boolean | Auto Destroy | Whether the returned audio component will be automatically cleaned up when the sound finishes (by completing or stopping) or whether it can be reactivated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | An audio component to manipulate the spawned sound |

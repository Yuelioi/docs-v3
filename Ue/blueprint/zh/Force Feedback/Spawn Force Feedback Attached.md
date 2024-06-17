---
title: Spawn Force Feedback Attached
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Force Feedback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ForceFeedback)

Plays a force feedback effect attached to and following the specified component. This is a fire and forget effect. Replication is also not handled at this point.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Force Feedback Effect | effect to play |
| object | Attach to Component |  |
| name | Attach Point Name | Optional named point within the AttachComponent to attach to |
| vector | Location | Depending on the value of Location Type this is either a relative offset from the attach component/point or an absolute world position that will be translated to a relative offset |
| rotator | Rotation | Depending on the value of Location Type this is either a relative offset from the attach component/point or an absolute world rotation that will be translated to a relative offset |
| enum | Location Type | Specifies whether Location is a relative offset or an absolute world position |
| boolean | Stop when Attached to Destroyed | Specifies whether the feedback effect should stop playing when the owner of the attach to component is destroyed. |
| boolean | Looping |  |
| real | Intensity Multiplier | Intensity multiplier |
| real | Start Time | How far in to the feedback effect to begin playback at |
| object | Attenuation Settings | Override attenuation settings package to play effect with |
| boolean | Auto Destroy | Whether the returned force feedback component will be automatically cleaned up when the feedback patern finishes (by completing or stopping) or whether it can be reactivated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Force Feedback Component to manipulate the playing feedback effect with |

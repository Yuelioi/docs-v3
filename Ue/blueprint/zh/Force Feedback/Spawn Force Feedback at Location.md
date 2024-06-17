---
title: Spawn Force Feedback at Location
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Force Feedback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ForceFeedback)

Plays a force feedback effect at the given location. This is a fire and forget effect and does not travel with any actor. Replication is also not handled at this point.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Force Feedback Effect | effect to play |
| vector | Location | World position to center the effect at |
| rotator | Rotation | World rotation to center the effect at |
| boolean | Looping |  |
| real | Intensity Multiplier | Intensity multiplier |
| real | Start Time | How far in to the feedback effect to begin playback at |
| object | Attenuation Settings | Override attenuation settings package to play effect with |
| boolean | Auto Destroy | Whether the returned force feedback component will be automatically cleaned up when the feedback pattern finishes (by completing or stopping) or whether it can be reactivated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Force Feedback Component to manipulate the playing feedback effect with |

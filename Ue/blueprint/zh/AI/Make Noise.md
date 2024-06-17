---
title: Make Noise
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI)

Trigger a noise caused by a given Pawn, at a given location.
Note that the NoiseInstigator Pawn MUST have a PawnNoiseEmitterComponent for the noise to be detected by a PawnSensingComponent.
Senders of MakeNoise should have an Instigator if they are not pawns, or pass a NoiseInstigator.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Loudness | The relative loudness of this noise. Usual range is 0 (no noise) to 1 (full volume). If MaxRange is used, this scales the max range, otherwise it affects the hearing range specified by the sensor. |
| object | Noise Instigator | Pawn responsible for this noise. Uses the actor's Instigator if NoiseInstigator is null |
| vector | Noise Location | Position of noise source. If zero vector, use the actor's location. |
| real | Max Range | Max range at which the sound may be heard. A value of 0 indicates no max range (though perception may have its own range). Loudness scales the range. (Note: not supported for legacy PawnSensingComponent, only for AIPerception) |
| name | Tag | Identifier for the noise. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

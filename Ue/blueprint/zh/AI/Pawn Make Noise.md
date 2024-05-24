---
display_name: Pawn Make Noise
order: 48
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI)

Inform AIControllers that you've made a noise they might hear (they are sent a HearNoise message if they have bHearNoises==true)
The instigator of this sound is the pawn which is used to call MakeNoise.

Target is Pawn

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Loudness | is the relative loudness of this noise (range 0.0 to 1.0). Directly affects the hearing range specified by the AI's HearingThreshold. |
| vector | Noise Location | Position of noise source. If zero vector, use the actor's location. |
| boolean | Use Noise Maker Location | If true, use the location of the NoiseMaker rather than NoiseLocation. If false, use NoiseLocation. |
| object | Noise Maker | Which actor is the source of the noise. Not to be confused with the Noise Instigator, which is responsible for the noise (and is the pawn on which this function is called). If not specified, the pawn instigating the noise will be used as the NoiseMaker |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

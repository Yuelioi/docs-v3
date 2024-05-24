---
display_name: Create Control Bus Mix Stage
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Creates a stage used to mix a control bus.

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Bus | Bus stage is in charge of applying mix value to. |
| real | Value | Value for added bus stage to target when mix is active. |
| real | Attack Time | Time in seconds for stage to mix in. |
| real | Release Time | Time in seconds for stage to mix out. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Stage |  |

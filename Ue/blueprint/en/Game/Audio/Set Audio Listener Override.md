---
display_name: Set Audio Listener Override
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Audio)

Used to override the default positioning of the audio listener

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Attach to Component | Optional component to attach the audio listener to |
| vector | Location | Depending on whether Component is attached this is either an offset from its location or an absolute position |
| rotator | Rotation | Depending on whether Component is attached this is either an offset from its rotation or an absolute rotation |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

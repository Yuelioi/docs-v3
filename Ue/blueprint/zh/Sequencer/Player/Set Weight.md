---
display_name: Set Weight
order: 46
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Player)

Set a manual weight to be multiplied with all blendable elements within this sequence
Note:: It is recommended that a weight between 0 and 1 is supplied, though this is not enforced
Note:: It is recommended that either FMovieSceneSequencePlaybackSettings::DynamicWeighting should be true for this player or the asset it's playing back should be set to enable dynamic weight to avoid undesirable behavior

Target is Movie Scene Sequence Player

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | In Weight | The weight to suuply to all elements in this sequence |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

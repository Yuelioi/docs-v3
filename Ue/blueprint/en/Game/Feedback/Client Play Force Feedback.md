---
display_name: Client Play Force Feedback
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Feedback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Feedback)

Play a force feedback pattern on the player's controller

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Force Feedback Effect | The force feedback pattern to play |
| name | Tag | A tag that allows stopping of an effect. If another effect with this Tag is playing, it will be stopped and replaced |
| boolean | Looping | Whether the pattern should be played repeatedly or be a single one shot |
| boolean | Ignore Time Dilation | Whether the pattern should ignore time dilation |
| boolean | Play While Paused | Whether the pattern should continue to play while the game is paused |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

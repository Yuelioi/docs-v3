---
display_name: Play Animation Time Range
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface/Animation)

Plays an animation in this widget a specified number of times stopping at a specified time

Target is User Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Animation | The animation to play |
| real | Start at Time | The time in the animation from which to start playing, relative to the start position. For looped animations, this will only affect the first playback of the animation. |
| real | End at Time | The absolute time in the animation where to stop, this is only considered in the last loop. |
| integer | Num Loops to Play | The number of times to loop this animation (0 to loop indefinitely) |
| enum | Play Mode | Specifies the playback mode |
| real | Playback Speed | The speed at which the animation should play |
| boolean | Restore State | Restores widgets to their pre-animated state when the animation stops |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |

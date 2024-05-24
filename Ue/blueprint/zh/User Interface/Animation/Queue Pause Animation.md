---
display_name: Queue Pause Animation
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface/Animation)

Pauses an already running animation in this widget

Target is User Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Animation |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | the time point the animation was at when it was paused, relative to its start position. Use this as the StartAtTime when you trigger PlayAnimation. |

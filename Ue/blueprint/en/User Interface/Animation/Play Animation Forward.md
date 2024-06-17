---
title: Play Animation Forward
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface/Animation)

Plays an animation on this widget relative to it's current state forward. You should use this version in situations where
say a user can click a button and that causes a panel to slide out, and you want to reverse that same animation to begin sliding
in the opposite direction.

Target is User Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Animation | The animation to play |
| real | Playback Speed | The speed at which the animation should play |
| boolean | Restore State | Restores widgets to their pre-animated state when the animation stops |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |

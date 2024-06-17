---
title: Project World Location to Widget Position
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Viewport](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Viewport)

Gets the projected world to screen position for a player, then converts it into a widget
position, which takes into account any quality scaling.

Target is Widget Layout Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Player Controller | The player controller to project the position in the world to their screen. |
| vector | World Location | The world location to project from. |
| boolean | Player Viewport Relative | Should this be relative to the player viewport subregion (useful when using player attached widgets in split screen or when aspect-ratio constrained) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector2d struct | Screen Position | The position in the viewport with quality scale removed and DPI scale remove. |
| boolean | Return Value | true if the position projects onto the screen. |

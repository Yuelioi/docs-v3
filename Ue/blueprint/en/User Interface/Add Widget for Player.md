---
title: Add Widget for Player
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [User Interface](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/UserInterface)

Adds the widget to the game's viewport in the section dedicated to the player. This is valuable in a split screen
game where you need to only show a widget over a player's portion of the viewport.

Target is Game Viewport Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Widget |  |
| object | Player |  |
| struct | Slot |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Adds the widget to the game's viewport in the section dedicated to the player. This is valuable in a split screengame where you need to only show a widget over a player's portion of the viewport. |

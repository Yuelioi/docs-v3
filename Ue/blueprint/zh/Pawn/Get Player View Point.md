---
title: Get Player View Point
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pawn](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn)

Returns Player's Point of View
For the AI this means the Pawn's 'Eyes' ViewPoint
For a Human player, this means the Camera's ViewPoint

@output out_Location, view location of player
@output out_rotation, view rotation of player

Target is Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Location |  |
| rotator | Rotation |  |

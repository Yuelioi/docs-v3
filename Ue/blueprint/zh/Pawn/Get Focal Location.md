---
title: Get Focal Location
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Pawn](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Pawn)

Returns the location the PlayerController is focused on.
If there is a possessed Pawn, returns the Pawn's location.
If there is a spectator Pawn, returns that Pawn's location.
Otherwise, returns the PlayerController's spawn location (usually the last known Pawn location after it has died).

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Return Value | Returns the location the PlayerController is focused on.If there is a possessed Pawn, returns the Pawn's location.If there is a spectator Pawn, returns that Pawn's location.Otherwise, returns the PlayerController's spawn location (usually the last known Pawn location after it has died). |

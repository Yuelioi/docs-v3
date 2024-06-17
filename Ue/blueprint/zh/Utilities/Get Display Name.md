---
title: Get Display Name
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

Returns the display name (or actor label), for displaying as a debugging aid.
Note: In editor builds, this is the actor label. In non-editor builds, this is the actual object name. This function should not be used to uniquely identify actors!
It is not localized and should not be used for display to an end user of a game.

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Object |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | Returns the display name (or actor label), for displaying as a debugging aid.Note: In editor builds, this is the actor label. In non-editor builds, this is the actual object name. This function should not be used to uniquely identify actors!It is not localized and should not be used for display to an end user of a game. |

---
display_name: Get Player Character
order: 38
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Returns the pawn for the player controller at the specified player index, will return null if the pawn is not a character.
This will not include characters of remote clients with no available player controller, you can iterate the PlayerStates list for that.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Player Index | Index in the player controller list, starting first with local players and then available remote ones |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |

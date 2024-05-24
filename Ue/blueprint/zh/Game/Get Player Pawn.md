---
display_name: Get Player Pawn
order: 40
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Returns the pawn for the player controller at the specified player index.
This will not include pawns of remote clients with no available player controller, you can use the player states list for that.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Player Index | Index in the player controller list, starting first with local players and then available remote ones |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |

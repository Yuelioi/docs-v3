---
display_name: Get Local Player Controller ID
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Gets what physical controller ID a player is using. This only works for local player controllers.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Player | The player controller of the player to get the ID of |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | The ID of the passed in player. -1 if there is no physical controller assigned to the passed in player |

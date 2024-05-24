---
display_name: Create Local Player
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Create a new local player for this game, for cases like local multiplayer.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Controller Id | The ID of the physical controller that the should control the newly created player. A value of -1 specifies to use the next available ID |
| boolean | Spawn Player Controller | Whether a player controller should be spawned immediately for this player. If false a player controller will not be created automatically until transition to the next map. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The created player controller if one is created. |

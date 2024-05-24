---
display_name: Quit Game
order: 37
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Exit the current game

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Specific Player | The specific player to quit the game. If not specified, player 0 will quit. |
| enum | Quit Preference | Form of quitting. |
| boolean | Ignore Platform Restrictions | Ignores and best-practices based on platform (e.g on some consoles, games should never quit). Non-shipping only |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

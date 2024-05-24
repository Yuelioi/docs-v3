---
display_name: Set Cinematic Mode
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Cinematic](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Cinematic)

Server/SP only function for changing whether the player is in cinematic mode. Updates values of various state variables, then replicates the call to the client
to sync the current cinematic mode.

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | In Cinematic Mode | specify true if the player is entering cinematic mode; false if the player is leaving cinematic mode. |
| boolean | Hide Player | specify true to hide the player's pawn (only relevant if bInCinematicMode is true) |
| boolean | Affects HUD | specify true if we should show/hide the HUD to match the value of bCinematicMode |
| boolean | Affects Movement | specify true to disable movement in cinematic mode, enable it when leaving |
| boolean | Affects Turning | specify true to disable turning in cinematic mode or enable it when leaving |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

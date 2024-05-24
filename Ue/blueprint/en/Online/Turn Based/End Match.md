---
display_name: End Match
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Online](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online) > [Turn Based](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online/TurnBased)

End a match that is in progress while it is the current player's turn

Target is End Match Callback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller |  |
| interface | Match Actor |  |
| string | Match ID |  |
| enum | Local Player Outcome |  |
| enum | Other Players Outcome |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when the match ends successfully |
| exec | On Failure | Called when ending the match fails |

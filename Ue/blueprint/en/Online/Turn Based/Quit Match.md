---
display_name: Quit Match
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Online](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online) > [Turn Based](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online/TurnBased)

Quits the turn based match

Target is Quit Match Callback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller |  |
| string | Match ID |  |
| enum | Outcome |  |
| integer | Turn Timeout in Seconds |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when there is a successful query |
| exec | On Failure | Called when there is an unsuccessful query |

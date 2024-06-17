---
title: Find Turn Based Match
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Online](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online) > [Turn Based](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online/TurnBased)

Use the platform matchmaking service (like Game Center) to find a match.

Target is Find Turn Based Match Callback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller |  |
| interface | Match Actor |  |
| integer | Min Players |  |
| integer | Max Players |  |
| integer | Player Group |  |
| boolean | Show Existing Matches |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when matchmaking succeeded. |
| exec | On Failure | Called when matchmaking failed |
| string | Match ID |  |

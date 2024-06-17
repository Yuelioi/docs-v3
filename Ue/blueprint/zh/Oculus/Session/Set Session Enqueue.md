---
title: Set Session Enqueue
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Oculus](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Oculus) > [Session](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Oculus/Session)

Kick off UpdateSession check. Asynchronous-- see OnUpdateCompleteDelegate for results.

Target is Oculus Update Session Callback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| boolean | Should Enqueue in Matchmaking Pool |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when the session was updated successfully |
| exec | On Failure | Called when there was an error updating the session |

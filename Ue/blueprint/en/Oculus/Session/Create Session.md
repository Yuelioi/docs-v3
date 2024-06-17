---
title: Create Session
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Oculus](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Oculus) > [Session](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Oculus/Session)

Kick off CreateSession check. Asynchronous-- see OnCreateSessionCompleteDelegate for results.

Target is Oculus Create Session Callback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Public Connections |  |
| string | Oculus Matchmaking Pool |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when the session was created successfully |
| exec | On Failure | Called when there was an error creating the session |

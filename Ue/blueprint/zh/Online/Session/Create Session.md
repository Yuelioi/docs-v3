---
title: Create Session
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Online](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online) > [Session](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online/Session)

Creates a session with the default online subsystem

Target is Create Session Callback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller |  |
| integer | Public Connections |  |
| boolean | Use LAN |  |
| boolean | Use Lobbies if Available |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when the session was created successfully |
| exec | On Failure | Called when there was an error creating the session |

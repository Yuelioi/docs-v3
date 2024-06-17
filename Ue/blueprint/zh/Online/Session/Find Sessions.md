---
title: Find Sessions
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Online](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online) > [Session](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Online/Session)

Searches for advertised sessions with the default online subsystem

Target is Find Sessions Callback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Player Controller |  |
| integer | Max Results |  |
| boolean | Use LAN |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when there is a successful query |
| exec | On Failure | Called when there is an unsuccessful query |
| struct | Results |  |

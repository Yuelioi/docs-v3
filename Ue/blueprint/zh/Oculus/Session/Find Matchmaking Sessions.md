---
title: Find Matchmaking Sessions
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Oculus](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Oculus) > [Session](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Oculus/Session)

Searches for matchmaking room sessions with the oculus online subsystem

Target is Oculus Find Sessions Callback Proxy

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| integer | Max Results |  |
| string | Oculus Matchmaking Pool |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Success | Called when there is a successful query |
| exec | On Failure | Called when there is an unsuccessful query |
| struct | Results |  |

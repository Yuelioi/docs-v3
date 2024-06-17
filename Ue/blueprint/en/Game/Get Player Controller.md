---
title: Get Player Controller
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Returns the player controller found while iterating through the local and available remote player controllers.
On a network client, this will only include local players as remote player controllers are not available.
The index will be consistent as long as no new players join or leave, but it will not be the same across different clients and servers.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Player Index | Index in the player controller list, starting first with local players and then available remote ones |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |

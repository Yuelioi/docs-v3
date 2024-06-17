---
title: Get Player State
order: 42
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Returns the player state at the given index in the game state's PlayerArray.
This will work on both the client and server and the index will be consistent.
After initial replication, all clients and the server will have access to PlayerStates for all connected players.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Player State Index | Index into the game state's PlayerArray |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value |  |

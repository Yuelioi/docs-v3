---
title: Get Ping in Milliseconds
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Player State](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PlayerState)

Returns the ping (in milliseconds)

Returns ExactPing if available (local players or when running on the server), and
the replicated CompressedPing (converted back to milliseconds) otherwise.

Note that replication of CompressedPing is controlled by bShouldUpdateReplicatedPing,
and if disabled then this will return 0 or a stale value on clients for player states
that aren't related to local players

Target is Player State

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value | Returns the ping (in milliseconds)Returns ExactPing if available (local players or when running on the server), andthe replicated CompressedPing (converted back to milliseconds) otherwise.Note that replication of CompressedPing is controlled by bShouldUpdateReplicatedPing,and if disabled then this will return 0 or a stale value on clients for player statesthat aren't related to local players |

---
title: Get Replicated Objects
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Multi-user](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Multi_user)

Gets the objects that are currently being replicated by the client.

Note: There is a difference between registered and replicated objects! Objects are registered with the server first and later the client
can attempt to start replicating them. GetReplicatedObjects() will always contain GetRegisteredObjects().

Target is Multi User Replication Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Client Id | The client of which to get the replicated objects. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The objects being replicated by the client |

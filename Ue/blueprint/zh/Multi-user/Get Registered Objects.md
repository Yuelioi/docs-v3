---
title: Get Registered Objects
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Multi-user](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Multi_user)

Gets the objects the client has registered with the server.

Just because an object is replicated, it does not mean that the object is being replicated.
Objects must be registered with the server so registration is just the first step.
GetReplicatedObjects() will always contain GetRegisteredObjects().

Target is Multi User Replication Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Client Id | The client of which to get the registered objects. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The objects the client has |

---
title: Add Additional Object (Message)
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Multi-user](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Multi_user)

Adds an additional object.

Properties will be automatically discovered for Object, as well.
If the object implements IMultiUserReplicationRegistrationContext, it will be invoked on Object recursively.

Target is Multi User Replication Registration Context

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Object | The additional object to add |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

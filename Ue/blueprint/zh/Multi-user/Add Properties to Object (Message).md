---
display_name: Add Properties to Object (Message)
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Multi-user](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Multi_user)

Extends the stream with the given object, if not yet added, and adds the properties to it.

Properties will be automatically discovered for Object, as well.
If the object implements IMultiUserReplicationRegistrationContext, it will be invoked on Object recursively.

Target is Multi User Replication Registration Context

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Object | Object to add, if not yet present, and assign a property to |
| struct | Properties to Add | Property chain to associate with the object |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

---
display_name: Change Client
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Multi-user](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Multi_user)

Allows changing of a client's stream and authority.

A stream is a mapping of objects to properties, i.e. registered objects.
A client must request to take authority over objects they have registered previously.
If there is no conflict with other clients, the server approves the request and the client starts replicating automatically.

Target is Change Client Async Action

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Client Id | The client for which this request is to be sent; can be the local or a remote client. |
| struct | Request | The request specifying a change to stream, authority, or both. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| exec | On Completed | Event that triggers when the operation completes. |
| struct | Response |  |

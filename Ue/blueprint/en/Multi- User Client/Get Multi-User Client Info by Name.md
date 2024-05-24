---
display_name: Get Multi-User Client Info by Name
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Multi- User Client](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Multi_UserClient)

Get the ClientInfo for any Multi-User participant by name. The local user is found even when not connected to a session. Returns false is no client was found.

Target is Multi User Client Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Client Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Client Info |  |
| boolean | Return Value | Get the ClientInfo for any Multi-User participant by name. The local user is found even when not connected to a session. Returns false is no client was found. |

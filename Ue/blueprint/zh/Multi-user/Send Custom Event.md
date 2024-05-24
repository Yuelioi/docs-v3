---
display_name: Send Custom Event
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Multi-user](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Multi_user)

Send a custom event message over multi-user. If you a not in an active session, this function does nothing and only
reports and warning to the output log.

Target is MultiUserSubsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| wildcard | Event Data | The event data to send. This must be the same type of UScriptStruct expected by the receivers on the registered handler. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

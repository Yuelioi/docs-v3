---
display_name: Register Custom Event Handler
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Multi-user](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Multi_user)

Register an event handler for the given type. Only one handler per type is allowed. You should register your handler
on session connected and remove the handler when the session disconnects.

Target is MultiUserSubsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Event Type | The struct type that we support handling. |
| delegate | In Event Handler |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the type handler was accepted. |

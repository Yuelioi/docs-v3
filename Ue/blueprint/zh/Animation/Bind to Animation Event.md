---
display_name: Bind to Animation Event
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation)

Allows binding to a specific animation's event.

Target is User Widget

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Animation | the animation to listen for starting or finishing. |
| delegate | Delegate | the delegate to call when the animation's state changes |
| enum | Animation Event | the event to watch for. |
| name | User Tag | Scopes the delegate to only be called when the animation completes with a specific tag set on it when it was played. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

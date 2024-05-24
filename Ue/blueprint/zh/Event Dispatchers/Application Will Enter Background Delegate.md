---
display_name: Application Will Enter Background Delegate
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Event Dispatchers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EventDispatchers)

This is called when the application is being backgrounded (e.g., due to switching
to another app or closing it via the home button)
The game should release shared resources, save state, etc..., since it can be
terminated from the background state without any further warning.

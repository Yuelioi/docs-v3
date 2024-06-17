---
title: Application Will Terminate Delegate
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Event Dispatchers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EventDispatchers)

This *may* be called when the application is getting terminated by the OS.
There is no guarantee that this will ever be called on a mobile device,
save state when ApplicationWillEnterBackgroundDelegate is called instead.

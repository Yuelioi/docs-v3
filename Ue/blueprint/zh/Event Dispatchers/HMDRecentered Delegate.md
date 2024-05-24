---
display_name: HMDRecentered Delegate
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Event Dispatchers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EventDispatchers)

This will be called when the XR runtime requests a recenter (such as when a system recenter button is pressed).
Whether or not the HMD will actually be recentered on the runtime side depends on the runtime, device, and current tracking space (local/stage).
By default, we do not automatically recenter on the application side. Recentering on either the runtime side or application side is sufficient to
recenter the user, and recentering on both sides at once is acceptable.

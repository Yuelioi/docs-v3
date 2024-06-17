---
title: OnPawnControllerChanged
order: 195
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Event Dispatchers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EventDispatchers)

gets triggered shortly after a pawn's controller is set. Most of the time
it signals that the Controller has changed but in edge cases (like during
replication) it might end up broadcasting the same pawn-controller pair
more than once

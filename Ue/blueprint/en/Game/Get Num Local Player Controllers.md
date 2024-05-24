---
display_name: Get Num Local Player Controllers
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Returns the number of fully initialized local players, this will be 0 on dedicated servers.
Indexes up to this can be used as PlayerIndex parameters for the following functions, and you are guaranteed to get a local player controller.

Target is Gameplay Statics

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| integer | Return Value | Returns the number of fully initialized local players, this will be 0 on dedicated servers.Indexes up to this can be used as PlayerIndex parameters for the following functions, and you are guaranteed to get a local player controller. |

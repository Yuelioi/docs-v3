---
title: On Actor Begin Overlap
order: 58
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Called when another actor begins to overlap this actor, for example a player walking into a trigger.
For events when objects have a blocking collision, for example a player hitting a wall, see 'Hit' events.

Components on both this and the other Actor must have bGenerateOverlapEvents set to true to generate overlap events.

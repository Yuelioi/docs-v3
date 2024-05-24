---
display_name: Event ActorBeginOverlap
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Add Event](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AddEvent) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AddEvent/Collision)

Event when this actor overlaps another actor, for example a player walking into a trigger.
For events when objects have a blocking collision, for example a player hitting a wall, see 'Hit' events.
Note: Components on both this and the other Actor must have bGenerateOverlapEvents set to true to generate overlap events.

Target is Actor

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| delegate | Output Delegate |  |
| exec | Out |  |
| object | Other Actor |  |

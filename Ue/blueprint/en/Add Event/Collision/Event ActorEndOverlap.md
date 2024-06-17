---
title: Event ActorEndOverlap
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Add Event](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AddEvent) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AddEvent/Collision)

Event when an actor no longer overlaps another actor, and they have separated.
Note: Components on both this and the other Actor must have bGenerateOverlapEvents set to true to generate overlap events.

Target is Actor

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| delegate | Output Delegate |  |
| exec | Out |  |
| object | Other Actor |  |

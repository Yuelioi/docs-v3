---
display_name: On Component Begin Overlap
order: 62
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Collision)

Event called when something starts to overlaps this component, for example a player walking into a trigger.
For events when objects have a blocking collision, for example a player hitting a wall, see 'Hit' events.

Both this component and the other one must have GetGenerateOverlapEvents() set to true to generate overlap events.
When receiving an overlap from another object's movement, the directions of 'Hit.Normal' and 'Hit.ImpactNormal'

will be adjusted to indicate force from the other object against this object.

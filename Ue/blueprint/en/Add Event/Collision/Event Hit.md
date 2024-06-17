---
title: Event Hit
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Add Event](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AddEvent) > [Collision](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AddEvent/Collision)

Event when this actor bumps into a blocking object, or blocks another actor that bumps into it.
This could happen due to things like Character movement, using Set Location with 'sweep' enabled, or physics simulation.
For events when objects overlap (e.g. walking into a trigger) see the 'Overlap' event.

Note: For collisions during physics simulation to generate hit events, 'Simulation Generates Hit Events' must be enabled.
Note: When receiving a hit from another object's movement (bSelfMoved is false), the directions of 'Hit.Normal' and 'Hit.ImpactNormal'
will be adjusted to indicate force from the other object against this object.
Note: NormalImpulse will be filled in for physics-simulating bodies, but will be zero for swept-component blocking collisions.

Target is Actor

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| delegate | Output Delegate |  |
| exec | Out |  |
| object | My Comp |  |
| object | Other |  |
| object | Other Comp |  |
| boolean | Self Moved |  |
| vector | Hit Location |  |
| vector | Hit Normal |  |
| vector | Normal Impulse |  |
| struct | Hit |  |

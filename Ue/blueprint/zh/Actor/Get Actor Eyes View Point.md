---
display_name: Get Actor Eyes View Point
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Actor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Actor)

Returns the point of view of the actor.
Note that this doesn't mean the camera, but the 'eyes' of the actor.
For example, for a Pawn, this would define the eye height location,
and view rotation (which is different from the pawn rotation which has a zeroed pitch component).
A camera first person view will typically use this view point. Most traces (weapon, AI) will be done from this view point.

Target is Actor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Out Location | location of view point |
| rotator | Out Rotation | view rotation of actor. |

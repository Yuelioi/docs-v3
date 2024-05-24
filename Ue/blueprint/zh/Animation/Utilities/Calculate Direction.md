---
display_name: Calculate Direction
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Utilities)

Returns degree of the angle between Velocity and Rotation forward vector
The range of return will be from \[-180, 180\]. Useful for feeding directional blendspaces.

Target is Kismet Animation Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| vector | Velocity | The velocity to use as direction relative to BaseRotation |
| rotator | Base Rotation | The base rotation, e.g. of a pawn |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Return Value |  |

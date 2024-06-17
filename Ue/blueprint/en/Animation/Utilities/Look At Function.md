---
title: Look At Function
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/Utilities)

Computes the transform which is "looking" at target position with a local axis.

Target is Kismet Animation Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Current Transform | The input transform to modify |
| vector | Target Position | The position this transform should look at |
| vector | Look at Vector | The local vector to align with the target |
| boolean | Use Up Vector | If set to true the lookat will also perform a twist rotation |
| vector | Up Vector | The position to use for the upvector target (only used is bUseUpVector is turned on) |
| real | Clamp Cone in Degree | A limit for only allowing the lookat to rotate as much as defined by the float value |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| transform | Return Value |  |

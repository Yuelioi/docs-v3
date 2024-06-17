---
title: Suggest Projectile Velocity
order: 56
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Calculates an launch velocity for a projectile to hit a specified point.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Start Location | Intended launch location |
| vector | End Location | Desired landing location |
| real | Launch Speed | Desired launch speed |
| real | Override Gravity Z | Optional gravity override. 0 means "do not override". |
| enum | Trace Option | Controls whether or not to validate a clear path by tracing along the calculated arc |
| real | Collision Radius | Radius of the projectile (assumed spherical), used when tracing |
| boolean | Favor High Arc | If true and there are 2 valid solutions, will return the higher arc. If false, will favor the lower arc. |
| boolean | Draw Debug | When true, a debug arc is drawn (red for an invalid arc, green for a valid arc) |
| boolean | Accept Closest on No Solutions | If target is unreachable and no solutions are possible, provide a velocity that gets as close to the target as possible given this launch speed |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Toss Velocity | (output) Result launch velocity. |
| boolean | Return Value | Returns false if there is no valid solution or the valid solutions are blocked. Returns true otherwise. |

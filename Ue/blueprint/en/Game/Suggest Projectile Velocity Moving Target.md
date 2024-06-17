---
title: Suggest Projectile Velocity Moving Target
order: 55
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Returns a launch velocity need for a projectile to hit the TargetActor in TimeToTarget seconds based on the TargetActor's current velocity.
This assumes the projectile is only accelerated by gravity (i.e. no outside forces), and that the TargetActor is moving at a constant velocity.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Projectile Start Location | Location the projectile is launched from |
| object | Target Actor | Actor that the projectile should hit in TimeToTarget seconds |
| vector | Target Location Offset | Offset to apply to the location the projectile is aiming for |
| real | Gravity ZOverride | Optional override of WorldGravityZ |
| real | Time to Target | Time (in seconds) between the projectile being launched and the projectile hitting the TargetActor - clamped to be at least 0.1 |
| enum | Draw Debug Type |  |
| real | Draw Debug Time |  |
| linearcolor | Draw Debug Color |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Out Launch Velocity | The launch velocity returned from this calculation |
| boolean | Return Value |  |

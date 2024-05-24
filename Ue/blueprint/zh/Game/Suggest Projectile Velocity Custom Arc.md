---
display_name: Suggest Projectile Velocity Custom Arc
order: 54
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game)

Returns the launch velocity needed for a projectile at rest at StartPos to land on EndPos.
Assumes a medium arc (e.g. 45 deg on level ground). Projectile velocity is variable and unconstrained.
Does no tracing.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Start Pos | Start position of the simulation |
| vector | End Pos | Desired end location for the simulation |
| real | Override Gravity Z | Optional override of WorldGravityZ |
| real | Arc Param | Change height of arc between 0.0-1.0 where 0.5 is the default medium arc, 0 is up, and 1 is directly toward EndPos. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Out Launch Velocity | Returns the launch velocity required to reach the EndPos |
| boolean | Return Value |  |

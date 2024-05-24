---
display_name: Apply Radial Damage with Falloff
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Damage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Damage)

Hurt locally authoritative actors within the radius. Will only hit components that block the Visibility channel.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | Base Damage | The base damage to apply, i.e. the damage at the origin. |
| real | Minimum Damage |  |
| vector | Origin | Epicenter of the damage area. |
| real | Damage Inner Radius | Radius of the full damage area, from Origin |
| real | Damage Outer Radius | Radius of the minimum damage area, from Origin |
| real | Damage Falloff | Falloff exponent of damage from DamageInnerRadius to DamageOuterRadius |
| class | Damage Type Class | Class that describes the damage that was done. |
| object | Ignore Actors | List of Actors to ignore |
| object | Damage Causer | Actor that actually caused the damage (e.g. the grenade that exploded) |
| object | Instigated by Controller | Controller that was responsible for causing this damage (e.g. player who threw the grenade) |
| enum | Damage Prevention Channel | Damage will not be applied to victim if there is something between the origin and the victim which blocks traces on this channel |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if damage was applied to at least one actor. |

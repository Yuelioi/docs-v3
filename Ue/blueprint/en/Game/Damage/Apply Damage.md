---
display_name: Apply Damage
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Damage](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Damage)

Hurts the specified actor with generic damage.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Damaged Actor | Actor that will be damaged. |
| real | Base Damage | The base damage to apply. |
| object | Event Instigator | Controller that was responsible for causing this damage (e.g. player who shot the weapon) |
| object | Damage Causer | Actor that actually caused the damage (e.g. the grenade that exploded) |
| class | Damage Type Class | Class that describes the damage that was done. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | Actual damage the ended up being applied to the actor. |

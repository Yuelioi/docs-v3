---
display_name: Give Ability
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Abilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayAbilities)

Grants a Gameplay Ability and returns its handle.
This will be ignored if the actor is not authoritative.

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Ability Class | Type of ability to grant |
| integer | Level | Level to grant the ability at |
| integer | Input ID | Input ID value to bind ability activation to. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value |  |

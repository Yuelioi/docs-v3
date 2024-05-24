---
display_name: Wait Gameplay Effect Applied to Actor
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Async](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Async)

Wait until a GameplayEffect is applied to a target actor
If TriggerOnce is true, this action will only activate one time. Otherwise it will return every time a GE is applied that meets the requirements over the life of the ability
If used in an ability graph, this async action will wait even after activation ends. It's recommended to use WaitGameplayEffectApplied instead.

Target is Ability Async Wait Gameplay Effect Applied

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Actor |  |
| struct | Source Filter |  |
| struct | Source Tag Requirements |  |
| struct | Target Tag Requirements |  |
| boolean | Trigger Once |  |
| boolean | Listen for Periodic Effect |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Action |  |
| exec | On Applied |  |
| object | Source |  |
| struct | Spec Handle |  |
| struct | Active Handle |  |

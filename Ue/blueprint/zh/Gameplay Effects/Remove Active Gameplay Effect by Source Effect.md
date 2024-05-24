---
display_name: Remove Active Gameplay Effect by Source Effect
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Effects](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayEffects)

Remove active gameplay effects whose backing definition are the specified gameplay effect class

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Gameplay Effect | Class of gameplay effect to remove; Does nothing if left null |
| object | Instigator Ability System Component | If specified, will only remove gameplay effects applied from this instigator ability system component |
| integer | Stacks to Remove | Number of stacks to remove, -1 means remove all |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

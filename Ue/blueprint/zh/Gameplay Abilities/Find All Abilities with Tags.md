---
display_name: Find All Abilities with Tags
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Abilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayAbilities)

Returns an array with all abilities that match the provided tags

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Tags | Gameplay Tags to match |
| boolean | Exact Match | If true, tags must be matched exactly. Otherwise, abilities matching any of the tags will be returned |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Ability Handles | This array will be filled with matching Ability Spec Handles |

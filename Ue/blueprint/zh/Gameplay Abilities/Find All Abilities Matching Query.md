---
title: Find All Abilities Matching Query
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Abilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayAbilities)

Returns an array with all abilities that match the provided Gameplay Tag Query

Target is Ability System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Query | Gameplay Tag Query to match |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Ability Handles | This array will be filled with matching Ability Spec Handles |

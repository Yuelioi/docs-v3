---
title: Perform Targeting Request
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Performs a targeting request based on a Targeting Preset from a GameplayAbility

Target is Ability Task Perform Targeting

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Targeting Preset |  |
| boolean | Allow Async |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Target Ready | Called when the targeting request has been completed and results are ready |
| struct | Targeting Request Handle |  |

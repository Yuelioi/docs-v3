---
display_name: Perform Filtering Request
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Performs a target filtering request based on a Targeting Preset from a GameplayAbility

Target is Ability Task Perform Targeting

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Targeting Preset |  |
| object | In Targets |  |
| boolean | Allow Async |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Target Ready | Called when the targeting request has been completed and results are ready |
| struct | Targeting Request Handle |  |

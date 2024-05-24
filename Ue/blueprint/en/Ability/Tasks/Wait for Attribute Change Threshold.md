---
display_name: Wait for Attribute Change Threshold
order: 46
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait on attribute change meeting a comparison threshold.

Target is Ability Task Wait Attribute Change Threshold

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Attribute |  |
| enum | Comparison Type |  |
| real | Comparison Value |  |
| boolean | Trigger Once |  |
| object | Optional External Owner |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Change |  |
| boolean | Matches Comparison |  |
| real | Current Value |  |

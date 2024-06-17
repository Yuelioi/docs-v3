---
title: Wait for Attribute Change Ratio Threshold
order: 45
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait on attribute ratio change meeting a comparison threshold.

Target is Ability Task Wait Attribute Change Ratio Threshold

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Attribute Numerator |  |
| struct | Attribute Denominator |  |
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
| real | Current Ratio |  |

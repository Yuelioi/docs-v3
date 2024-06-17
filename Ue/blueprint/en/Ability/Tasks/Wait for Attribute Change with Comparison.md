---
title: Wait for Attribute Change with Comparison
order: 47
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until an attribute changes to pass a given test.

Target is Ability Task Wait Attribute Change

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | In Attribute |  |
| struct | In with Tag |  |
| struct | In Without Tag |  |
| enum | In Comparison Type |  |
| real | In Comparison Value |  |
| boolean | Trigger Once |  |
| object | Optional External Owner |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Change |  |

---
title: Wait for Ability Activate with Tag Requirements
order: 43
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until a new ability (of the same or different type) is activated. Only input based abilities will be counted unless IncludeTriggeredAbilities is true. Uses a tag requirements structure to filter abilities.

Target is Ability Task Wait Ability Activate

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Tag Requirements |  |
| boolean | Include Triggered Abilities |  |
| boolean | Trigger Once |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Activate |  |
| object | Activated Ability |  |

---
display_name: Wait for Ability Activate Query
order: 42
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until a new ability (of the same or different type) is activated. Only input based abilities will be counted unless IncludeTriggeredAbilities is true.

Target is Ability Task Wait Ability Activate

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Query |  |
| boolean | Include Triggered Abilities |  |
| boolean | Trigger Once |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Activate |  |
| object | Activated Ability |  |

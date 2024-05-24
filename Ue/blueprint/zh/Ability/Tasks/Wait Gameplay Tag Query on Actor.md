---
display_name: Wait Gameplay Tag Query on Actor
order: 33
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until the given gameplay tag query has become true or false, based on TriggerCondition, looking at the target actors ASC.
If the the tag query already satisfies the TriggerCondition when this task is started, it will immediately broadcast the Triggered
event. It will keep listening as long as bOnlyTriggerOnce = false.
If used in an ability graph, this async action will wait even after activation ends. It's recommended to use WaitGameplayTagQuery instead.

Target is Ability Async Wait Gameplay Tag Query

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Actor |  |
| struct | Tag Query |  |
| enum | Trigger Condition |  |
| boolean | Only Trigger Once |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Action |  |
| exec | Triggered | This delegate will be triggered when the trigger condition has been met. |

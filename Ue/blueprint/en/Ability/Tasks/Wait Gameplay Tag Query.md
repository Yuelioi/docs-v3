---
display_name: Wait Gameplay Tag Query
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until the given gameplay tag query has become true or false, based on TriggerCondition.
By default this will look at the owner of this ability. OptionalExternalTarget can be set to
make this look at another actor's tags for changes. If the the tag query already satisfies
the TriggerCondition when this task is started, it will immediately broadcast the Triggered
event. It will keep listening as long as bOnlyTriggerOnce = false.

Target is Ability Task Wait Gameplay Tag Query

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Tag Query |  |
| object | In Optional External Target |  |
| enum | Trigger Condition |  |
| boolean | Only Trigger Once |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | Triggered | This delegate will be triggered when the trigger condition has been met. |

---
title: Wait Gameplay Event
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until the specified gameplay tag event is triggered. By default this will look at the owner of this ability. OptionalExternalTarget can be set to make this look at another actor's tags for changes
It will keep listening as long as OnlyTriggerOnce = false
If OnlyMatchExact = false it will trigger for nested tags

Target is Ability Task Wait Gameplay Event

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Event Tag |  |
| object | Optional External Target |  |
| boolean | Only Trigger Once |  |
| boolean | Only Match Exact |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | Event Received |  |
| struct | Payload |  |

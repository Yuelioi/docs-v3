---
title: Wait Gameplay Tag Add to Actor
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until the specified gameplay tag is Added to Target Actor's ability component
If the tag is already present when this task is started, it will immediately broadcast the Added event. It will keep listening as long as OnlyTriggerOnce = false.
If used in an ability graph, this async action will wait even after activation ends. It's recommended to use WaitGameplayTagAdd instead.

Target is Ability Async Wait Gameplay Tag Added

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Actor |  |
| struct | Tag |  |
| boolean | Only Trigger Once |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Action |  |
| exec | Added |  |

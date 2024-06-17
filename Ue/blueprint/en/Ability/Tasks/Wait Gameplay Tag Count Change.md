---
title: Wait Gameplay Tag Count Change
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until the specified gameplay tag count has changed. By default this will look at the owner of this ability. OptionalExternalTarget can be set to make this look at another actor's tags for changes.

Target is Ability Task Wait Gameplay Tag Count Changed

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Tag |  |
| object | In Optional External Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | Tag Count Changed |  |
| integer | Tag Count |  |

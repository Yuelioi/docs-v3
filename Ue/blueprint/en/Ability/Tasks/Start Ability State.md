---
title: Start Ability State
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Starts a new ability state.

Target is Ability Task Start Ability State

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | State Name | The name of the state. |
| boolean | End Current State | If true, all other active ability states will be ended. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On State Ended | Invoked if 'EndAbilityState' is called or if 'EndAbility' is called and this state is active. |
| exec | On State Interrupted | Invoked if the ability was interrupted and this state is active. |

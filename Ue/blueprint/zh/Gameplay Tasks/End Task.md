---
title: End Task
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayTasks)

Called explicitly to end the task (usually by the task itself). Calls OnDestroy.
Note:: you need to call EndTask before sending out any "on completed" delegates.
If you don't the task will still be in an "active" state while the event receivers may
assume it's already "finished"

Target is Gameplay Task

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

---
title: Get Completion
order: 45
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Gets the current completion for an agent. Should be called only after GatherCompletions.

Target is Learning Agents Trainer

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Agent Id | The AgentId to look-up the completion for |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| enum | Return Value | The completion type |

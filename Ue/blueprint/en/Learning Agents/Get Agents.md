---
title: Get Agents
order: 33
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Gets the agents associated with a set of ids. Calling this from blueprint with the appropriate AgentClass will
automatically cast the object to the given type.

Target is Learning Agents Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Agent Ids | The ids of the agents to get. |
| class | Agent Class | The class to cast the agent objects to (in blueprint). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Agents | The output array of agent objects. |

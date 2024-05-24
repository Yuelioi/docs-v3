---
display_name: Get Agent
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Gets the agent with the given id. Calling this from blueprint with the appropriate AgentClass will automatically
cast the object to the given type. If not in a blueprint, you should use one of the other GetAgent overloads.

Target is Learning Agents Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Agent Id | The id of the agent to get. |
| class | Agent Class | The class to cast the agent object to (in blueprint). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | The agent object. |

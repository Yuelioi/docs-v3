---
display_name: Get Action Vector
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Get the current buffered action vector for the given agent.

Target is Learning Agents Interactor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Agent Id | Agent Id to look up the action vector for. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Out Action Vector | Output Action Vector |
| integer | Out Action Compatibility Hash | Output Compatibility Hash used to identify which schema this vector is compatible with. |

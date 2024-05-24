---
display_name: Set Observation Vector
order: 267
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Sets the current buffered observation vector for the given agent.

Target is Learning Agents Interactor

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Observation Vector | Observation Vector |
| integer | In Observation Compatibility Hash | Compatibility Hash used to identify which schema this vector is compatible with. |
| integer | Agent Id | Agent Id to set the observation vector for. |
| boolean | Increment Iteration | If to increment the iteration number used to keep track of associated actions and observations. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

---
display_name: Specify Float Action
order: 301
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new float action. This represents an action which is a single float sampled from a Gaussian distribution. It can be used as a
catch-all for situations where a type-specific action does not exist.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Action Schema |
| name | Tag | The tag of this new action. Used during action object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created action schema element. |

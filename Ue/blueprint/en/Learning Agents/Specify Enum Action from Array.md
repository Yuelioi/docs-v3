---
display_name: Specify Enum Action from Array
order: 292
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new enum action. This represents an action which is an exclusive choice from entries of an Enum, sampled from a Categorical distribution.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Action Schema |
| object | Enum | The Enum type. |
| real | Prior Probabilities | The prior probabilities of each enum element. Can be left empty to use a uniform distribution over elements. Should sum to one. |
| name | Tag | The tag of this new action. Used during action object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created action schema element. |

---
display_name: Specify Bitmask Action
order: 278
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new bitmask action. This represents an action which is an inclusive choice from entries of an Enum, sampled from a Bernoulli
distribution.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Action Schema |
| object | Enum | The Enum type. |
| byte | Prior Probabilities | The prior probabilities of each enum element. Can be left empty to use a probability of 0.5 for each element. |
| name | Tag | The tag of this new action. Used during action object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created action schema element. |

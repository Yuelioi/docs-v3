---
display_name: Specify Inclusive Discrete Action
order: 303
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new inclusive discrete action. This represents an action which is an inclusive choice from a number of discrete options, sampled
from a Bernoulli distribution.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Action Schema |
| integer | Size | The number of discrete options in the action. |
| real | Prior Probabilities | The prior probabilities of each option. Can be left empty to use a probability of 0.5 for each option. |
| name | Tag | The tag of this new action. Used during action object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created action schema element. |

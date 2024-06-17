---
title: Specify Exclusive Discrete Action
order: 295
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new exclusive discrete action. This represents an action which is an exclusive choice from a number of discrete options, sampled
from a Categorical distribution.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Action Schema |
| integer | Size | The number of discrete options in the action. |
| real | Prior Probabilities | The prior probabilities of each option. Can be left empty to use a uniform distribution over options. Should sum to one. |
| name | Tag | The tag of this new action. Used during action object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created action schema element. |

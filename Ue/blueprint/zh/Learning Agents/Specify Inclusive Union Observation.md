---
title: Specify Inclusive Union Observation
order: 308
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new inclusive union observation. This represents an observation which is inclusively chosen from a set of named sub-observations.
In other words, when this observation is created, you can provide any combination of observations from the given sub-observations. Internally
this observation uses Attention so can be slower to evaluate and more difficult to train than other observation types. For this reason it
should be used sparingly.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Observation Schema |
| name | Elements | The sub-observations that make up this union. |
| integer | Attention Encoding Size | The encoding size used by the attention mechanism. |
| integer | Attention Head Num | The number of heads used by the attention mechanism. |
| integer | Value Encoding Size | The output encoding size used by the attention mechanism. |
| name | Tag | The tag of this new observation. Used during observation object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation schema element. |

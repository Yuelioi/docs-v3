---
title: Specify Set Observation
order: 325
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new set observation. This represents an observation made up of a Set of some other observation. This Set can be variable in size
(up to some fixed maximum size) and elements are considered unordered. Internally this observation uses Attention so can be slower to evaluate
and more difficult to train than other observation types. For this reason it should be used sparingly.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Observation Schema |
| struct | Element | The sub-observation that represents elements of this array. |
| integer | Max Num | The maximum number of elements that can be included in the set. |
| integer | Attention Encoding Size | The encoding size used by the attention mechanism. |
| integer | Attention Head Num | The number of heads used by the attention mechanism. |
| integer | Value Encoding Size | The output encoding size used by the attention mechanism. |
| name | Tag | The tag of this new observation. Used during observation object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation schema element. |

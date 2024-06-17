---
title: Specify Encoding Observation
order: 291
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new encoding observation. This represents an observation which will be an encoding of another sub-observation using a small neural
network.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Observation Schema |
| struct | Element | The sub-observation to be encoded. |
| integer | Encoding Size | The encoding size used to encode this sub-observation. |
| integer | Hidden Layer Num | The number of hidden layers used to encode this sub-observation. |
| enum | Activation Function | The activation function used to encode this sub-observation. |
| name | Tag |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation schema element. |

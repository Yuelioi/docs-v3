---
display_name: Specify Exclusive Discrete Observation
order: 296
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new exclusive discrete observation. This represents a discrete observation which is an exclusive selection from multiple choices.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Observation Schema |
| integer | Size | The number of discrete options in the observation. |
| name | Tag | The tag of this new observation. Used during observation object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation schema element. |

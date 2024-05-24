---
display_name: Specify Array Observation
order: 276
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new array observation. This represents an observation made up of an Array of some other observation. This Array can be variable in
size (up to some fixed maximum size) and the order of elements is taken into consideration. Internally this observation uses Attention so can
be slower to evaluate and more difficult to train than other observation types. For this reason it should be used sparingly.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Observation Schema |
| struct | Element | The sub-observation that represents elements of this array. |
| integer | Max Num | The maximum number of elements that can be included in the array. |
| integer | Attention Encoding Size | The encoding size used by the attention mechanism. |
| integer | Attention Head Num | The number of heads used by the attention mechanism. |
| integer | Value Encoding Size | The output encoding size used by the attention mechanism. |
| name | Tag | The tag of this new observation. Used during observation object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation schema element. |

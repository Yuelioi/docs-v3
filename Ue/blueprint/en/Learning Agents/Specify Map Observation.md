---
display_name: Specify Map Observation
order: 312
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new map observation. This represents an observation made up of a Map of some other key and pair observations. This Map can be
variable in size (up to some fixed maximum size) and elements are considered unordered. Internally this observation uses Attention so can
be slower to evaluate and more difficult to train than other observation types. For this reason it should be used sparingly.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Observation Schema |
| struct | Key Element | The sub-observation that represents keys in this map. |
| struct | Value Element | The sub-observation that represents values in this map. |
| integer | Max Num | The maximum number of elements that can be included in the map. |
| integer | Attention Encoding Size | The encoding size used by the attention mechanism. |
| integer | Attention Head Num | The number of heads used by the attention mechanism. |
| integer | Value Encoding Size | The output encoding size used by the attention mechanism. |
| name | Tag | The tag of this new observation. Used during observation object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation schema element. |

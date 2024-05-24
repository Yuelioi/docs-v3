---
display_name: Specify Exclusive Union Observation from Arrays
order: 299
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new exclusive union observation. This represents an observation which is exclusively chosen from a set of named sub-observations.
In other words, when this observation is created, you only need to provide one observation from the given sub-observations.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Observation Schema |
| name | Element Names | The names of the sub-observations that make up this union. |
| struct | Elements | The corresponding sub-observations that make up this union. Must be the same size as ElementNames. |
| integer | Encoding Size | The encoding size used to encode each sub-observation. |
| name | Tag | The tag of this new observation. Used during observation object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation schema element. |

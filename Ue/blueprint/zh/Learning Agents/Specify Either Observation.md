---
display_name: Specify Either Observation
order: 289
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new either observation. This represents an observation which will be either sub-observation A or sub-observation B.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Observation Schema |
| struct | A | The first sub-observation. |
| struct | B |  |
| integer | Encoding Size | The encoding size used to encode each sub-observation. |
| name | Tag |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation schema element. |

---
display_name: Validate Observation Object Matches Schema
order: 337
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Validates that the given observation object matches the schema. Will log errors on objects that don't match.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Schema | Observation Schema |
| struct | Schema Element | Observation Schema Element |
| object | Object | Observation Object |
| struct | Object Element | Observation Object Element |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the object matches the schema |

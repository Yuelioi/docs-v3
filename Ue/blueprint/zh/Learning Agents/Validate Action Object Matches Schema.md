---
display_name: Validate Action Object Matches Schema
order: 336
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Validates that the given action object matches the schema. Will log errors on objects that don't match.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Schema | Action Schema |
| struct | Schema Element | Action Schema Element |
| object | Object | Action Object |
| struct | Object Element | Action Object Element |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the object matches the schema |

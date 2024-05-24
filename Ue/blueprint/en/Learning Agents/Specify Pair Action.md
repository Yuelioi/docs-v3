---
display_name: Specify Pair Action
order: 317
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new pair action. This represents an action which is made up of a key and value sub-actions.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Action Schema |
| struct | Key | The key sub-action. |
| struct | Value | The value sub-action. |
| name | Tag | The tag of this new action. Used during action object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created action schema element. |

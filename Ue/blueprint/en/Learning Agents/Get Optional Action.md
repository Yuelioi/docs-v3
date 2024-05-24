---
display_name: Get Optional Action
order: 97
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Get the sub-action of an option action.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The Action Object |
| struct | Element | The Action Object Element |
| name | Tag | The tag of the corresponding action. Must match the tag given during Specify. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Null |  |
| exec | Valid |  |
| struct | Out Element | The output sub-action. |
| boolean | Success | true if the provided Element is the correct type, otherwise false. |

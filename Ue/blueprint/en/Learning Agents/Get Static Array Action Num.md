---
display_name: Get Static Array Action Num
order: 117
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Get the number of entries in a static array action.

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
| exec | Out |  |
| integer | Out Num | The output number of entries. |
| boolean | Success | true if the provided Element is the correct type, otherwise false. |

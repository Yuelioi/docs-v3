---
display_name: Make Completion on Condition
order: 161
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Make a completion based on some condition.

Target is Learning Agents Completions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Condition | When true, returns the given CompletionType, otherwise returns Running. |
| enum | Completion Type | The type of completion to make. |
| name | Tag | The tag for the completion. Used for debugging. |
| boolean | Visual Logger Enabled | When true, debug data will be sent to the visual logger. |
| object | Visual Logger Listener | The listener object which is making this completion. This must be set to use logging. |
| integer | Visual Logger Agent Id | The agent id associated with this completion. |
| vector | Visual Logger Location | A location for the visual logger information in the world. |
| linearcolor | Visual Logger Color | The color for the visual logger display. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| enum | Return Value | The resulting completion. |

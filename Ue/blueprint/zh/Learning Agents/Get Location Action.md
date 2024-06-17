---
title: Get Location Action
order: 83
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Get the value for a location action.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The Action Object |
| struct | Element | The Action Object Element |
| transform | Relative Transform | The relative transform to transform the location by. |
| real | Location Scale | The scale used to control the overall magnitude of the outputted location action. |
| name | Tag | The tag of the corresponding action. Must match the tag given during Specify. |
| boolean | Visual Logger Enabled | When true, debug data will be sent to the visual logger. |
| object | Visual Logger Listener | The listener object which is making this action. This must be set to use logging. |
| integer | Visual Logger Agent Id | The agent id associated with this action. |
| vector | Visual Logger Location | A location for the visual logger information in the world. |
| linearcolor | Visual Logger Color | The color for the visual logger display. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Out Location | The output location value. |
| boolean | Success | true if the provided Element is the correct type, otherwise false. |

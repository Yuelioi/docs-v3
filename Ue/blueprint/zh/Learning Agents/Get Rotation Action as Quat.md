---
title: Get Rotation Action as Quat
order: 108
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Get the value for a rotation action as a quaternion.

Target is Learning Agents Actions

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The Action Object |
| struct | Element | The Action Object Element |
| struct | Relative Rotation | The relative rotation to transform the rotation by. |
| real | Rotation Scale | The scale used to control the overall magnitude of the outputted rotation action. |
| name | Tag | The tag of the corresponding action. Must match the tag given during Specify. |
| boolean | Visual Logger Enabled | When true, debug data will be sent to the visual logger. |
| object | Visual Logger Listener | The listener object which is making this action. This must be set to use logging. |
| integer | Visual Logger Agent Id | The agent id associated with this action. |
| vector | Visual Logger Rotation Location | A location for the visual logger to display the rotation in the world. |
| vector | Visual Logger Location | A location for the visual logger information in the world. |
| linearcolor | Visual Logger Color | The color for the visual logger display. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Rotation | The output rotation value. |
| boolean | Success | true if the provided Element is the correct type, otherwise false. |

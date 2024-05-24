---
display_name: Make Proportion Along Ray Observation
order: 216
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Make a new proportion along ray observation.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Object | The Observation Object |
| vector | Ray Start | The local ray start location. |
| vector | Ray End | The local ray end location. |
| transform | Ray Transform | The transform to use to transform the local ray starts and ends into the world space. |
| enum | Collision Channel | The collision channel to collide against. |
| name | Tag | The tag of the corresponding observation. Must match the tag given during Specify. |
| boolean | Visual Logger Enabled | When true, debug data will be sent to the visual logger. |
| object | Visual Logger Listener | The listener object which is making this observation. This must be set to use logging. |
| integer | Visual Logger Agent Id | The agent id associated with this observation. |
| vector | Visual Logger Location | A location for the visual logger information in the world. |
| linearcolor | Visual Logger Color | The color for the visual logger display. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation object element. |

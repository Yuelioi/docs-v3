---
display_name: Make Inclusive Discrete Observation
order: 194
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Make a new inclusive discrete observation.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Object | The Observation Object |
| integer | Discrete Indices | The indices of the discrete observations. All values must be smaller than the given Size. |
| integer | Size | The size of the discrete observation. Must be equal to the size given during Specify. |
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

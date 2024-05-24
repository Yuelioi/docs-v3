---
display_name: Make Direction Observation
order: 175
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Make a new direction observation.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Object | The Observation Object |
| vector | Direction | The direction of interest to the agent. |
| transform | Relative Transform | The transform the provided direction should be encoded relative to. |
| name | Tag | The tag of the corresponding observation. Must match the tag given during Specify. |
| boolean | Visual Logger Enabled | When true, debug data will be sent to the visual logger. |
| object | Visual Logger Listener | The listener object which is making this observation. This must be set to use logging. |
| integer | Visual Logger Agent Id | The agent id associated with this observation. |
| vector | Visual Logger Direction Location | A location for the visual logger to display the direction in the world. |
| vector | Visual Logger Location | A location for the visual logger information in the world. |
| real | Visual Logger Arrow Length | The length of the arrow to display to represent the direction. |
| linearcolor | Visual Logger Color | The color for the visual logger display. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation object element. |

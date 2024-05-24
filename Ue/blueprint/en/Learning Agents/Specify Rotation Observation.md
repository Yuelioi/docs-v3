---
display_name: Specify Rotation Observation
order: 322
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Learning Agents](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LearningAgents)

Specifies a new rotation observation. Allows an agent to observe the rotation of some entity. Rotations are encoded as two columns of the
rotation matrix to ensure there is no discontinuity in the encoding.

Target is Learning Agents Observations

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Schema | The Observation Schema |
| name | Tag | The tag of this new observation. Used during observation object validation and debugging. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | The newly created observation schema element. |

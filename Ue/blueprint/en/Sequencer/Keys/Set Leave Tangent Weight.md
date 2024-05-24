---
display_name: Set Leave Tangent Weight
order: 110
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Keys](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Keys)

If Tangent Weight Mode is RCTWM_WeightedLeave or RCTWM_WeightedBoth, the weight of the leaving tangent on the right side.

Target is Movie Scene Scripting Float Key

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | In New Value | Specifies the new leaving tangent weight. Represents the length of the hypotenuse in the form of "sqrt(x*x+y*y)" using the same definitions for x and y as tangents. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

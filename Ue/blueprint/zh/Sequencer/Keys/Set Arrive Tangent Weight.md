---
display_name: Set Arrive Tangent Weight
order: 99
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Sequencer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer) > [Keys](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Sequencer/Keys)

If Tangent Weight Mode is RCTWM_WeightedArrive or RCTWM_WeightedBoth, the weight of the arriving tangent on the left side.

Target is Movie Scene Scripting Double Key

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | In New Value | Specifies the new arriving tangent weight. Represents the length of the hypotenuse in the form of "sqrt(x*x+y*y)" using the same definitions for x and y as tangents. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

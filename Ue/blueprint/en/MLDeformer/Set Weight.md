---
display_name: Set Weight
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [MLDeformer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MLDeformer)

Set the ML Deformer weight. This determines how active the deformer is. You can see it as a blend weight.
A value of 0 means it is inactive. Certain calculations will be skipped in that case.
A value of 1 means it is fully active.
Values between 0 and 1 blend between the two states.
Call this after you call SetupComponent.

Target is MLDeformer Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Normalized Weight Value | The weight value. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

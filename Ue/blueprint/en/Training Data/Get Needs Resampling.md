---
display_name: Get Needs Resampling
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Training Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TrainingData)

Check whether we need to resample the inputs and outputs, or if we can use a cached version.
This will return true if any inputs changed, that indicate that we should regenerate any cached data.

Target is MLDeformer Training Model

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true when we need to regenerate any cached data, otherwise false is returned. |

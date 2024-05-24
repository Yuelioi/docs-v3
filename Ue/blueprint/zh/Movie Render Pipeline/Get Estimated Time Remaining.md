---
display_name: Get Estimated Time Remaining
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Render Pipeline](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieRenderPipeline)

Get the estimated amount of time remaining for the current pipeline. Based on looking at the total
amount of samples to render vs. how many have been completed so far. Inaccurate when Time Dilation
is used, and gets more accurate over the course of the render.

Target is Movie Pipeline Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | In Pipeline | The pipeline to get the time estimate from. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Out Estimate | The resulting estimate, or FTimespan() if estimate is not valid. |
| boolean | Return Value | True if a valid estimate can be calculated, or false if it is not ready yet (ie: not enough samples rendered) |

---
display_name: Interpolate to Value
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Numeric Interpolation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NumericInterpolation)

Starts an ongoing process of interpolating the current numeric value to the specified target value.
The interpolation process may take the specified maximum duration or complete sooner if the minimum change rate causes the target to be reached prematurely.
Optionally, an outro duration can be specified in order to trigger an outro event before interpolation completes.

TargetValue The value to be interpolated to.
MaximumInterpolationDuration The duration, in seconds, for the interpolation to take, at most. Must be greater than 0.
MinimumChangeRate The minimum change in numeric value per second. Must be greater than or equal to 0.
OutroDuration The time offset, in seconds, *before* the end of the InterpolationDuration elapses, at which to trigger an outro event. Must be less than or equal to MaximumInterpolationDuration

Target is Common Numeric Text Block

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Target Value |  |
| real | Maximum Interpolation Duration |  |
| real | Minimum Change Rate |  |
| real | Outro Offset |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

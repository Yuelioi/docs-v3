---
title: Vector Spring Interp
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Math](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math) > [Interpolation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Math/Interpolation)

Uses a simple spring model to interpolate a vector from Current to Target.

Target is Kismet Math Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Current | Current value |
| vector | Target | Target value |
| struct | Spring State | Data related to spring model (velocity, error, etc..) - Create a unique variable per spring |
| real | Stiffness | How stiff the spring model is (more stiffness means more oscillation around the target value) |
| real | Critical Damping Factor | How much damping to apply to the spring (0 means no damping, 1 means critically damped which means no oscillation) |
| real | Delta Time | Time difference since the last update |
| real | Mass | Multiplier that acts like mass on a spring |
| real | Target Velocity Amount | If 1 then the target velocity will be calculated and used, which results following the target more closely/without lag. Values down to zero (recommended when using this to smooth data) will progressively disable this effect. |
| boolean | Clamp | Whether to use the Min/Max values to clamp the motion |
| vector | Min Value | Clamps the minimum output value and cancels the velocity if it reaches this limit |
| vector | Max Value | Clamps the maximum output value and cancels the velocity if it reaches this limit |
| boolean | Initialize from Target | If set then the current value will be set from the target on the first update |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Return Value |  |

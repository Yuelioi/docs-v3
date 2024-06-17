---
title: Set Haptics by Value
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Feedback](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Feedback)

Sets the value of the haptics for the specified hand directly, using frequency and amplitude. NOTE: If a curve is already
playing for this hand, it will be cancelled in favour of the specified values.

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Frequency | The normalized frequency \[0.0, 1.0\] to play through the haptics system |
| real | Amplitude | The normalized amplitude \[0.0, 1.0\] to set the haptic feedback to |
| enum | Hand | Which hand to play the effect on |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

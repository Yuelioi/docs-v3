---
title: Set View Target with Blend
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Player)

Set the view target blending with variable control

Target is Player Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | New View Target | new actor to set as view target |
| real | Blend Time | time taken to blend |
| enum | Blend Func | Cubic, Linear etc functions for blending |
| real | Blend Exp | Exponent, used by certain blend functions to control the shape of the curve. |
| boolean | Lock Outgoing | If true, lock outgoing viewtarget to last frame's camera position for the remainder of the blend. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

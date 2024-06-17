---
title: Start Broadcasting
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Motion Design Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MotionDesignMedia)

Start broadcasting all channels.
Returns true on partial success, i.e. will be true even if some channels didn't start.
Outputs error messages related to outputs that caused problems.

Target is Motion Design Broadcast Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Out Error Message |  |
| boolean | Return Value | Start broadcasting all channels.Returns true on partial success, i.e. will be true even if some channels didn't start.Outputs error messages related to outputs that caused problems. |

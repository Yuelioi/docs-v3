---
title: Get Effective Frame Rate
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

If InNode is valid, inspects the provided OutputsettingNode to determine if it wants to override the
Frame Rate, and if so, returns the overwritten frame rate. If nullptr, or it does not have the
bOverride_bUseCustomFrameRate flag set, then InDefaultrate is returned.

Target is Movie Graph Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | In Node | Optional, setting to inspect for a custom framerate. |
| struct | In Default Rate | The frame rate to use if the node is nullptr or doesn't want to override the rate. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | The effective frame rate (taking into account the node's desire to override it). |

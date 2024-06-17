---
title: Get Camera View
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Camera)

Returns camera's Point of View.
Called by Camera class. Subclass and postprocess to add any effects.

Target is Camera Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| real | Delta Time |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Desired View |  |

---
title: Clear All Global Control Bus Mix Values
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Clears all global control bus mix values if set, using the applied fade time to return all to their respective bus's parameter default value.

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | Fade Time | Fade time to user when interpolating between current value and new values. If non-positive, change is immediate. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

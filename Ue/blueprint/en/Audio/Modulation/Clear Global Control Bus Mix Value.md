---
title: Clear Global Control Bus Mix Value
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Clears global control bus mix if set, using the applied fade time to return to the provided bus's parameter default value.

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Bus | Bus associated with mix to update |
| real | Fade Time | Fade time to user when interpolating between current value and new values. If non-positive, change is immediate. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

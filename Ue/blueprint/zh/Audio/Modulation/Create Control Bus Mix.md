---
title: Create Control Bus Mix
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Modulation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Modulation)

Creates a modulation bus mix, with a bus stage set to the provided target value.

Target is Audio Modulation Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Name | Name of mix. |
| struct | Stages | Stages mix is responsible for. |
| boolean | Activate | Whether or not to activate mix on creation. If true, deactivation will only occur if returned mix is manually deactivated and not referenced or destroyed (i.e. will not deactivate when all references become inactive). |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Bus Mix | Capture this in a Blueprint variable to prevent it from being garbage collected. |

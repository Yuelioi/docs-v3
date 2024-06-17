---
title: Get Player Mapped Key
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [VCam Input](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VCamInput)

Searches the currently active input system for the current key mapped to a given input mapping
If there is not a player mapped key, then this will return EKeys::Invalid.

Target is VCam Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Mapping Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Key | Searches the currently active input system for the current key mapped to a given input mappingIf there is not a player mapped key, then this will return EKeys::Invalid. |

---
title: Expose Property
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Remote Control Preset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RemoteControlPreset)

Expose a property in a remote control preset.

Target is Remote Control Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Preset | the preset to expose the property in. |
| object | Source Object | the object that contains the property to expose. |
| string | Property | the name or path of the property to expose. |
| struct | Args | optional arguments. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether the operation was successful. |

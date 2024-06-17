---
title: Get Attenuation Settings To Apply
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media) > [Media Sound Component](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media/MediaSoundComponent)

Get the attenuation settings based on the current component settings.

Target is Media Sound Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Attenuation Settings | Will contain the attenuation settings, if available. |
| boolean | Return Value | true if attenuation settings were returned, false if attenuation is disabled. |

---
title: Get Plugin Version Name
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Engine Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EngineScripting) > [Plugin Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EngineScripting/PluginUtilities)

Get the version name of a plugin.

Target is Plugin Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Plugin Name | Name of the plugin |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Out Version Name | Version name of the plugin, if found |
| boolean | Return Value | true if the named plugin was found and the plugin's version name was stored in OutVersionName, or false otherwise |

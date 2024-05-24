---
display_name: Get Plugin Description
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Engine Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EngineScripting) > [Plugin Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EngineScripting/PluginUtilities)

Get the description of a plugin.

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
| string | Out Description | Description of the plugin, if found |
| boolean | Return Value | true if the named plugin was found and the plugin's description was stored in OutDescription, or false otherwise |

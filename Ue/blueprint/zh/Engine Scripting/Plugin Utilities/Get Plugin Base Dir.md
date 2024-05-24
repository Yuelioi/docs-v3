---
display_name: Get Plugin Base Dir
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Engine Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EngineScripting) > [Plugin Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EngineScripting/PluginUtilities)

Get the filesystem path to a plugin's base directory.

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
| string | Out Base Dir | Filesystem path to the plugin's base directory, if found |
| boolean | Return Value | true if the named plugin was found and the plugin base directory filesystem path was stored in OutBaseDir, or false otherwise |

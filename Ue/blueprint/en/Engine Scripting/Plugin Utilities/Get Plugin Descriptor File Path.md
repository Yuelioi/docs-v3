---
display_name: Get Plugin Descriptor File Path
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Engine Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EngineScripting) > [Plugin Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EngineScripting/PluginUtilities)

Get the filesystem path to a plugin's descriptor.

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
| string | Out File Path | Filesystem path to the plugin's descriptor, if found |
| boolean | Return Value | true if the named plugin was found and the plugin descriptor filesystem path was stored in OutFilePath, or false otherwise |

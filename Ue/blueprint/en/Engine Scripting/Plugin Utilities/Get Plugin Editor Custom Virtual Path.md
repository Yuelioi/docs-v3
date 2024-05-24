---
display_name: Get Plugin Editor Custom Virtual Path
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Engine Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EngineScripting) > [Plugin Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EngineScripting/PluginUtilities)

Get the editor custom virtual path of a plugin.

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
| string | Out Virtual Path | Editor custom virtual path of the plugin, if found |
| boolean | Return Value | true if the named plugin was found and the plugin's editor custom virtual path was stored in OutVirtualPath, or false otherwise |

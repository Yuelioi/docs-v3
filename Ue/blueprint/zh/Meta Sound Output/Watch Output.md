---
title: Watch Output
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Meta Sound Output](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MetaSoundOutput)

Watch an output on a Metasound playing on a given audio component.

Target is Meta Sound Output Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Audio Component | The audio component |
| name | Output Name | The user-specified name of the output in the Metasound |
| delegate | On Output Value Changed | The event to fire when the output's value changes |
| name | Analyzer Name | (optional) The name of the analyzer to use on the output, defaults to a passthrough |
| name | Analyzer Output Name | (optional) The name of the output on the analyzer to watch, defaults to the passthrough output |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the watch setup succeeded, false otherwise |

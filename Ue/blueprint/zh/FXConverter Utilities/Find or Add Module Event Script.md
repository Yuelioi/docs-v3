---
title: Find or Add Module Event Script
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [FXConverter Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/FXConverterUtilities)

Find a module script conversion context or add a module script conversion context to this emitter conversion context for an event category. If a script conversion context
is not found by name string then a new one is created and initialized from the NiagaraScriptAssetData.

Target is Niagara Emitter Conversion Context

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Script Name String |  |
| struct | Create Script Context Args |  |
| struct | Event Script Props |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Find a module script conversion context or add a module script conversion context to this emitter conversion context for an event category. If a script conversion contextis not found by name string then a new one is created and initialized from the NiagaraScriptAssetData. |

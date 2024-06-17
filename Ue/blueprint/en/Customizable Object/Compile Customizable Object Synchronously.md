---
title: Compile Customizable Object Synchronously
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Customizable Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/CustomizableObject)

Synchronously compiles the provided CustomizableObject, LogMutable will contain intermittent updates on
progress.

Target is Customizable Object Editor Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Customizable Object | The CustomizableObject to compile |
| enum | Optimization Level |  |
| enum | Texture Compression |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| enum | Return Value | The final ECustomizableObjectCompilationState - typically Completed or Failed |

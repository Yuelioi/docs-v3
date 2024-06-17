---
title: Load Blueprint Class
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Asset_1)

Load a Blueprint asset and return its generated class. It will verify if the object is already loaded and only load it if it's necessary.

Target is Editor Asset Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Asset Path | Asset Path of the Blueprint asset. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| class | Return Value | Found or loaded class. |

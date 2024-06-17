---
title: Rename Referencing Soft Object Paths (Message)
order: 40
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/AssetTools)

Function that renames all FSoftObjectPath object with the old asset path to the new one.

Target is Asset Tools

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Packages to Check | Packages to check for referencing FSoftObjectPath. |
| struct | Asset Redirector Map | Map from old asset path to new asset path |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

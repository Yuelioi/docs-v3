---
title: Construct Datasmith Scene from Source Uri
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Datasmith)

Open an existing Datasmith source from the SourceUri.

Target is Datasmith Scene Element

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Source Uri | Uri of the datasmith scene to open. ie: file://c:/MyFolder/MyFiles.udatasmith |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The opened DatasmithScene, that can be modified and can be imported. |

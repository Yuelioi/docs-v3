---
title: Get All Datasmith User Data
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Datasmith User Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/DatasmithUserData)

Find all Datasmith User Data of loaded objects of the given type.
This is a slow operation, so editor only.

Target is Datasmith Content Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Object Class | Class of the object on which to filter, if specificed; otherwise there's no filtering |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out User Data | Output array of Datasmith User Data. |

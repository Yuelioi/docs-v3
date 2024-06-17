---
title: Get All Objects and Values for Key
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Datasmith User Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/DatasmithUserData)

Find all loaded objects of the given type that have a Datasmith User Data that contains the given key and their associated values.
This is a slow operation, so editor only.

Target is Datasmith Content Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Key | The key to find in the Datasmith User Data. |
| class | Object Class | Class of the object on which to filter, if specificed; otherwise there's no filtering |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Objects | Output array of objects for which the Datasmith User Data match the given key. |
| string | Out Values | Output array of values associated with each object in OutObjects. |

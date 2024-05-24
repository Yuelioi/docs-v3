---
display_name: Get All Objects and Values for Key
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith) > [Scene](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Datasmith/Scene)

Find all objects of the given type that have a metadata element that contains the given key and their associated values.

Target is Datasmith Scene Element Base

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Key | The key to find in the metadata element. |
| class | Object Class | Class of the object on which to filter, if specificed; otherwise there's no filtering |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Objects | Output array of objects for which the metadata element contains the given key. |
| string | Out Values | Output array of values associated with each object in OutObjects. |

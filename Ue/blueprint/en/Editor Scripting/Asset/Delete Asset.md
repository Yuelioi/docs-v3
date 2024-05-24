---
display_name: Delete Asset
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Asset_1)

Delete the package the assets live in. All objects that live in the package will be deleted.
This is a Force Delete. It doesn't check if the asset has references in other Levels or by Actors.
It will close all the asset editors and may clear the Transaction buffer (Undo History).
Will try to mark the file as deleted. The Asset will be loaded before being deleted.

Target is Editor Asset Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Asset Path to Delete | Asset Path of the asset that we want to delete. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the operation succeeds. |

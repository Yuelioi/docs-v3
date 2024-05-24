---
display_name: Delete Loaded Asset
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Asset_1)

Delete an asset that is already loaded.
This is a Force Delete. It does not check if the asset has references in other Levels or by Actors.
It will close all the asset editors and may clear the Transaction buffer (Undo History).
Will try to mark the file as deleted.

Target is Editor Asset Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Asset to Delete | Asset to delete. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the operation succeeds. |

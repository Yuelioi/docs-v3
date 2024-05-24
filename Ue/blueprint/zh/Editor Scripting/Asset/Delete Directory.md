---
display_name: Delete Directory
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Asset_1)

Delete the packages inside a directory. If the directory is then empty, delete the directory.
This is a Force Delete. It does not check if the assets have references in other Levels or by Actors.
It will close all the asset editors and may clear the Transaction buffer (Undo History).
Will try to mark the file as deleted. Assets will be loaded before being deleted.
The search is always recursive. It will try to delete the sub folders.

Target is Editor Asset Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Directory Path | Directory that will be marked for deletion and deleted. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | True if the operation succeeds. |

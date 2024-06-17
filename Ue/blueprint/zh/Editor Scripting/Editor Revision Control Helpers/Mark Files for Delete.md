---
title: Mark Files for Delete
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Revision Control Helpers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorRevisionControlHelpers)

Use currently set source control provider to remove files from source control and delete the files.
Note: Blocks until action is complete.

Target is Source Control Helpers

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | In Files |  |
| boolean | Silent | if false (default) then write out any error info to the Log. Any error text can be retrieved by LastErrorMsg() regardless. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if succeeded, false if failed and can call LastErrorMsg() for more info. |

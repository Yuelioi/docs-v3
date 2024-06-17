---
title: Check in Files
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Revision Control Helpers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorRevisionControlHelpers)

Use currently set source control provider to check in specified files.
Note: Blocks until action is complete.

Target is Source Control Helpers

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | In Files | Files to check out - can be either fully qualified path, relative path, long package name, asset path or export text path (often stored on clipboard) |
| string | In Description | Description for check in |
| boolean | Silent | if false (default) then write out any error info to the Log. Any error text can be retrieved by LastErrorMsg() regardless. |
| boolean | Keep Checked Out | Keep files checked-out after checking in. This is helpful for maintaining "ownership" of files if further operations are needed. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if succeeded, false if failed and can call LastErrorMsg() for more info. |

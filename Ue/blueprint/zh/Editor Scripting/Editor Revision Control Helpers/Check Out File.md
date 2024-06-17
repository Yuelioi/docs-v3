---
title: Check Out File
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Revision Control Helpers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorRevisionControlHelpers)

Use currently set source control provider to check out a file.
Note: Blocks until action is complete.

Target is Source Control Helpers

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | In File | The file to check out - can be either fully qualified path, relative path, long package name, asset path or export text path (often stored on clipboard) |
| boolean | Silent | if false (default) then write out any error info to the Log. Any error text can be retrieved by LastErrorMsg() regardless. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if succeeded, false if failed and can call LastErrorMsg() for more info. |

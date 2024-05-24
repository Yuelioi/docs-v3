---
display_name: Copy File
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Revision Control Helpers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorRevisionControlHelpers)

Use currently set source control provider to copy a file.
Note: Blocks until action is complete.

Target is Source Control Helpers

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | In Source File | Source file string to copy from - can be either fully qualified path, relative path, long package name, asset path or export text path (often stored on clipboard) |
| string | In Dest File | Source file string to copy to - can be either fully qualified path, relative path, long package name, asset path or export text path (often stored on clipboard). If package, then uses same extension as source file. |
| boolean | Silent | if false (default) then write out any error info to the Log. Any error text can be retrieved by LastErrorMsg() regardless. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if succeeded, false if failed and can call LastErrorMsg() for more info. |

---
display_name: Async Query File State
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Editor Revision Control Helpers](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/EditorRevisionControlHelpers)

Query the source control state of the specified file, asynchronously.

Target is Source Control Helpers

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| delegate | File State Callback | Source control state - see USourceControlState. It will have bIsValid set to false if it could not have its values set. |
| string | In File | The file to query - can be either fully qualified path, relative path, long package name, asset path or export text path (often stored on clipboard) |
| boolean | Silent | if false (default) then write out any error info to the Log. Any error text can be retrieved by LastErrorMsg() regardless. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

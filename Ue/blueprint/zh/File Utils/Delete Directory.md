---
display_name: Delete Directory
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [File Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/FileUtils)

Deletes a directory and all the files in it and optionally all sub-directories and files within it

Target is Blueprint File Utils BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Directory | The Directory to delete |
| boolean | Must Exist | If true, the directory must exist or the return value will be false |
| boolean | Delete Recursively | If true, all sub-directories will be deleted as well. If false and there are contents in the directory, the delete operation will fail. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the directory was succesfully deleted, false otherwise |

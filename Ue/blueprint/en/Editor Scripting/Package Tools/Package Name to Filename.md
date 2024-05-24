---
display_name: Package Name to Filename
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Package Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/PackageTools)

Converts a long package name to a file name.
This can be called on package paths as well, provide no extension in that case.
Will return an empty string if it fails.

Target is Package Tools

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Package Name | Long Package Name |
| string | Extension | Package extension. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | Package filename, or empty if it failed. |

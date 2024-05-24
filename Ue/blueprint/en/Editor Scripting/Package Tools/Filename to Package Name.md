---
display_name: Filename to Package Name
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Package Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/PackageTools)

Tries to convert a given relative or absolute filename to a long package name or path starting with a root like /Game
This works on both package names and directories, and it does not validate that it actually exists on disk.

Target is Package Tools

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Filename | Filename to convert. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Return Value | Resulting long package name if the supplied filename properly maps to a long package root, empty string otherwise. |

---
display_name: Construct Datasmith Scene from File
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Datasmith)

Open an existing UDatasmith file from disk.

Target is Datasmith Scene Element

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | File Path | UDatasmith file path to open. ie: c:/MyFolder/MyFiles.udatasmith |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The opened DatasmithScene, that can be modified and can be imported. |

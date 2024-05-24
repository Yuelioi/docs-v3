---
display_name: Construct Datasmith Scene from CADFiles
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Datasmith)

Open set of CAD files as actors in a single datasmith scene
Importing set of files into single DatasmithScene asset(with ImportScene) is supported only for CAD files

Target is Datasmith Scene Element

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | File Paths |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The opened DatasmithScene, that can be modified and can be imported. |

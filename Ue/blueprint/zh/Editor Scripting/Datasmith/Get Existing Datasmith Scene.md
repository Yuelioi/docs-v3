---
display_name: Get Existing Datasmith Scene
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Datasmith](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Datasmith)

Open an existing DatasmithScene asset file from disk.

Target is Datasmith Scene Element

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Asset Path | Path of the DFatasmithScene asset (eg. "/Game/MyAsset") |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The opened DatasmithScene, that can be modified and can be reimported. |

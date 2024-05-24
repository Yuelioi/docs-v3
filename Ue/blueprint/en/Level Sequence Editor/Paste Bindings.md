---
display_name: Paste Bindings
order: 43
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Level Sequence Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LevelSequenceEditor)

Paste bindings
Paste bindings from the given TextToImport string (used in conjunction with CopyBindings).
If TextToImport is empty, the contents of the clipboard will be used.

Target is Level Sequence Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Text to Import |  |
| struct | Paste Bindings Params |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Object Bindings |  |
| boolean | Return Value | Paste bindingsPaste bindings from the given TextToImport string (used in conjunction with CopyBindings).If TextToImport is empty, the contents of the clipboard will be used. |

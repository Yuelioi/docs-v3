---
display_name: Paste Sections
order: 45
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Level Sequence Editor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LevelSequenceEditor)

Paste sections
Paste sections from the given TextToImport string (used in conjunction with CopySections).
If TextToImport is empty, the contents of the clipboard will be used.

Target is Level Sequence Editor Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Text to Import |  |
| struct | Paste Sections Params |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Sections |  |
| boolean | Return Value | Paste sectionsPaste sections from the given TextToImport string (used in conjunction with CopySections).If TextToImport is empty, the contents of the clipboard will be used. |

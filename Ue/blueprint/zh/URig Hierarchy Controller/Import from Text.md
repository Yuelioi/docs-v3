---
display_name: Import from Text
order: 21
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [URig Hierarchy Controller](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/URigHierarchyController)

Imports the content of a text buffer to the hierarchy

Target is Rig Hierarchy Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Content | The string buffer representing the content to import |
| boolean | Replace Existing Elements | If set to true existing items will be replaced / updated with the content in the buffer |
| boolean | Select New Elements | If set to true the new elements will be selected |
| boolean | Setup Undo | If set to true the stack will record the change for undo / redo |
| boolean | Print Python Commands |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value |  |

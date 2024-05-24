---
display_name: Show Objects Dialog
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Objects Dialog](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/ObjectsDialog)

Open a modal message box dialog containing a details view for inspecting / modifying multiples UObjects.

Target is Editor Dialog Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| text | Title | The title of the created dialog window |
| object | In Out Objects | Array of object instances which are supposed to be viewed |
| struct | Options | Optional settings to customize the look of the details view |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | The result of the users decision, true=Ok, false=Cancel, or false if running in unattended mode. |

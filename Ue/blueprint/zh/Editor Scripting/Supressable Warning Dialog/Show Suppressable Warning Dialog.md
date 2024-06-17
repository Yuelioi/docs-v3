---
title: Show Suppressable Warning Dialog
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Supressable Warning Dialog](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/SupressableWarningDialog)

Open a modal suppressable warning window, if suppressed will return the default value

Target is Editor Dialog Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| text | Title | The title of the created dialog window |
| text | Message | Text of the message to show |
| string | In Ini Setting Name | The name of the entry in the INI where the state of the "Disable this warning" check box is stored |
| string | In Ini Setting File Name Override | The name of the INI where the state of the InIniSettingName flag is stored (defaults to GEditorPerProjectIni) |
| boolean | Default Value | If the warning is suppressed, the function will log and return DefaultValue |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | The result of the users decision, or DefaultValue if suppressed. |

---
title: Show Message Dialog
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Message Dialog](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/MessageDialog)

Open a modal message box dialog with the given message. If running in "-unattended" mode it will immediately
return the value specified by DefaultValue. If not running in "-unattended" mode then it will block execution
until the user makes a decision, at which point their decision will be returned.

Target is Editor Dialog Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| text | Title | The title of the created dialog window |
| text | Message | Text of the message to show |
| enum | Message Type | Specifies which buttons the dialog should have |
| enum | Default Value | If the application is Unattended, the function will log and return DefaultValue |
| enum | Message Category | The category of the message (affects the icon used) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| enum | Return Value | The result of the users decision, or DefaultValue if running in unattended mode. |

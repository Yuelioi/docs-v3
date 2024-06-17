---
title: Request Speak Focused Widget
order: 13
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Requests the information about the accessibility widget a user is focused on to be read out.
If nothing is currently being focused on by the screen reader user, nothing will be read out.
The same guarantees about the announcement being spoken in RequestSpeak() apply for this function.
Nothing will happen if the passed in user Id is not already registered with the screen reader.

Target is Slate Screen Reader Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Screen Reader User Id | The user Id to request its accessible focus to be read out |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | FScreenReaderReply::Handled() if the user's focused widget's information is successfully spoken. Else FScreenReaderReply::Unhandled() is returned. |

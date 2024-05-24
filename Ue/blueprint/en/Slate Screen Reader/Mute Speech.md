---
display_name: Mute Speech
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Mutes the text to speech for a screen reader user.
If the provided user Id doesn't exist, nothing will happen.

Target is Slate Screen Reader Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Screen Reader User Id | The user Id of the screen reader user to mute text to speech for. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | FScreenReaderReply::Handled() is returned if the screen reader user is successfully muted. Otherwise, FScreenReaderReply::Unhandled() is returned. |

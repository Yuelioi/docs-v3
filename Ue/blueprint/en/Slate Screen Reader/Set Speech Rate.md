---
display_name: Set Speech Rate
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Sets the rate text to speech will be speaking at for a screen reader user.
If the provided user Id doesn't exist, nothing will happen.

Target is Slate Screen Reader Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Screen Reader User Id | The user Id of the screen reader user to set the text to speech rate for |
| real | Rate | The rate text to speech will be set at for the provided screen reader user. Value will be clamped between 0.0f and 1.0f. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | FScreenReaderReply::Handled() is returned if the speech rate is successfully set for the screen reader user. Otherwise, FScreenReaderReply::Unhandled() is returned. |

---
display_name: Activate User
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Activates a screen reader user and fulfill requests for accessibility services such as text to speech that clients can make.
When screen reader users are first registered with a screen reader, they are deactivated by default. Users must explicitly activate the screen reader user.
If the passed in user Id does not correspond to a registered screen reader user, nothing will happen.

Target is Slate Screen Reader Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Screen Reader User Id | The user Id of the screen reader user to request activation |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | FScreenReaderReply::Handled() if the screen reader user is successfully activated. Else FScreenReaderReply::Unhandled() is returned. |

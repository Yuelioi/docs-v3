---
display_name: Stop Speaking
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Immediately stops speaking any currently spoken announcement for a particular screen reader user.
Does nothing if there is no announcement currently being spoken for the user or if the user Id is not registered with the screen reader.

Target is Slate Screen Reader Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Screen Reader User Id | The user Id of the screen reader user to request announcements to be stopped. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | FScreenReader::Handled() if the request to stop speaking is successfully processed. Else FScreenReaderReply::Unhandled() is returned. |

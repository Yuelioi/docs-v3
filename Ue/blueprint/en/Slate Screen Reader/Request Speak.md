---
title: Request Speak
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Requests an announcement to be spoken to the screen reader user. This is the main mechanism to provide text to speech auditory feedback
to end users.
Calling this function does not guarantee that the announcement will be spoken via text to speech and be
heard by a user.
All announcements spoken via text to speech will be asynchronous and will not block the game thread.
If the screen reader user is active and no announcements are currently spoken, the announcement will be spoken immediately.
If another announcement is currently being spoken, the passed in announcement could be queued or interrupt the currently spoken announcement.

Target is Slate Screen Reader Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Screen Reader User Id | The user Id of the screen reader user the announcement is intended for |
| struct | Announcement | The announcement requested to be spoken to the screen reader user |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Return Value | FScreenReaderReply::Handled() if the request was successfully processed. Else return FScreenReader::Unhandled() |

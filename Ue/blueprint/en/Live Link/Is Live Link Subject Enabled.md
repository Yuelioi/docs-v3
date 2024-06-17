---
title: Is Live Link Subject Enabled
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Live Link](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LiveLink)

Whether or not the client has a subject with this name enabled
Only 1 subject with the same name can be enabled.
At the start of the frame, a snapshot of the enabled subjects will be made.
That snapshot dictate which subject will be used for the duration of that frame.

Target is Live Link Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Subject Name |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether or not the client has a subject with this name enabledOnly 1 subject with the same name can be enabled.At the start of the frame, a snapshot of the enabled subjects will be made.That snapshot dictate which subject will be used for the duration of that frame. |

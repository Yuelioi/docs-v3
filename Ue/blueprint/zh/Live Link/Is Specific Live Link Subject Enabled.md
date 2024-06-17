---
title: Is Specific Live Link Subject Enabled
order: 36
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Live Link](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LiveLink)

Whether or not a subject from the specific source is the enabled subject.
Only 1 subject with the same name can be enabled.
At the start of the frame, a snapshot of the enabled subjects will be made.
That snapshot dictate which subject will be used for the duration of that frame.

Target is Live Link Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Subject Key |  |
| boolean | For This Frame |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether or not a subject from the specific source is the enabled subject.Only 1 subject with the same name can be enabled.At the start of the frame, a snapshot of the enabled subjects will be made.That snapshot dictate which subject will be used for the duration of that frame. |

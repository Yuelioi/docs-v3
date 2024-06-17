---
title: Set Live Link Subject Enabled
order: 41
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Live Link](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LiveLink)

Set the subject's from a specific source to enabled, disabling the other in the process.
Only 1 subject with the same name can be enabled.
At the start of the frame, a snapshot of the enabled subjects will be made.
That snapshot dictate which subject will be used for the duration of that frame.
SetSubjectEnabled will take effect on the next frame.

Target is Live Link Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Subject Key |  |
| boolean | Enabled |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

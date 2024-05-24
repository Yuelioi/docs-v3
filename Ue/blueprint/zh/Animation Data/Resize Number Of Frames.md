---
display_name: Resize Number Of Frames
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimationData)

Sets the total play-able length in seconds. Broadcasts a EAnimDataModelNotifyType::SequenceLengthChanged notify if successful.
T0 and T1 are expected to represent the window of time that was either added or removed. E.g. for insertion T0 indicates the time
at which additional time starts and T1 were it ends. For removal T0 indicates the time at which time should be started to remove, and T1 indicates the end. Giving a total of T1 - T0 added or removed length.
The number of frames and keys for the provided length is recalculated according to the current value of UAnimDataModel::FrameRate.

Target is Animation Data Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| struct | New Length in Frames | Total new play-able number of frames value (according to frame rate), has to be positive and non-zero |
| struct | T0 | Point between 0 and NewLengthInFrames at which the change in length starts |
| struct | T1 | Point between 0 and NewLengthInFrames at which the change in length ends |
| boolean | Should Transact | Whether or not any undo-redo changes should be generated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

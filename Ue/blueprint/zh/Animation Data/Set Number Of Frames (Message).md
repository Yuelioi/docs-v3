---
display_name: Set Number Of Frames (Message)
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AnimationData)

Sets the total play-able length in seconds. Broadcasts a EAnimDataModelNotifyType::SequenceLengthChanged notify if successful.
The number of frames and keys for the provided length is recalculated according to the current value of UAnimDataModel::FrameRate.

Target is Animation Data Controller

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | New Length in Frames | Total new play-able number of frames value (according to frame rate), has to be positive and non-zero |
| boolean | Should Transact | Whether or not any undo-redo changes should be generated |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

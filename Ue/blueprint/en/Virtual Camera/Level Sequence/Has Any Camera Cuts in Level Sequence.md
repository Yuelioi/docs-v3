---
title: Has Any Camera Cuts in Level Sequence
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera) > [Level Sequence](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera/LevelSequence)

Checks whether this sequence has any camera cuts set up.

If yes, you should pilot the sequence using ULevelSequenceEditorBlueprintLibrary::SetLockCameraCutToViewport instead of directly piloting
by using FindLevelSequencePilotableCamerasInActiveLevelSequence.

Target is Level Sequence VCam Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Sequence |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Checks whether this sequence has any camera cuts set up.If yes, you should pilot the sequence using ULevelSequenceEditorBlueprintLibrary::SetLockCameraCutToViewport instead of directly pilotingby using FindLevelSequencePilotableCamerasInActiveLevelSequence. |

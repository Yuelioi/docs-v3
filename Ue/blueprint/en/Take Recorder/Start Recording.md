---
title: Start Recording
order: 25
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Take Recorder](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/TakeRecorder)

Start a new recording using the specified parameters. Will fail if a recording is currently in progress

Target is Take Recorder Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Level Sequence | The base level sequence to use for the recording. Will be played back during the recording and duplicated to create the starting point for the resulting asset. |
| object | Sources | The sources to use for the recording |
| object | Meta Data | Meta-data pertaining to this recording, duplicated into the resulting recorded sequence |
| struct | Parameters | Configurable parameters for this recorder instance |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The recorder responsible for the recording, or None if a a recording could not be started |

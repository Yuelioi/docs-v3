---
title: Set Drop Timecode Frame Number
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Media](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Media)

Convert frame number into a drop timecode

Target is Linear Timecode Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Timecode | used to access the framerate, and drop flag |
| integer | Frame Number | Frame number to set in the returned timecode |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Timecode | Returned drop timecode |

---
title: Fetch Timecode
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Provider](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Provider)

Fetch current timecode from its source. e.g. From hardware/network/file/etc.
It is recommended to cache the fetched timecode.

Target is Timecode Provider

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Frame Time |  |
| boolean | Return Value | Fetch current timecode from its source. e.g. From hardware/network/file/etc.It is recommended to cache the fetched timecode. |

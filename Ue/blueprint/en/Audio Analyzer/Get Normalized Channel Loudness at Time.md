---
title: Get Normalized Channel Loudness at Time
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio Analyzer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AudioAnalyzer)

Get a specific channel normalized loudness of the analyzed sound at a given time. Normalized
loudness is always between 0.0 to 1.0. 0.0 refers to the noise floor while 1.0 refers to the
maximum loudness in the sound.

Target is Loudness NRT

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | In Seconds |  |
| integer | In Channel |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Out Loudness |  |

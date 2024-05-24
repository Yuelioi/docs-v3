---
display_name: Get Normalized Channel Onsets Between Times
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio Analyzer](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AudioAnalyzer)

Get a specific channel cqt of the analyzed sound at a given time.

Target is Onset NRT

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | In Start Seconds |  |
| real | In End Seconds |  |
| integer | In Channel |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| real | Out Onset Timestamps |  |
| real | Out Onset Strengths |  |

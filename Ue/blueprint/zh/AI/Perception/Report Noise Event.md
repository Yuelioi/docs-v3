---
title: Report Noise Event
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Perception](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Perception)

Report a noise event.

Target is AISense Hearing

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| vector | Noise Location | Location of the noise. |
| real | Loudness | Loudness of the noise. If MaxRange is non-zero, modifies MaxRange, otherwise modifies the squared distance of the sensor's range. |
| object | Instigator | Actor that triggered the noise. |
| real | Max Range | Max range at which the sound can be heard, multiplied by Loudness. Values \<= 0 mean no limit (still limited by listener's range however). |
| name | Tag | Identifier for the event. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

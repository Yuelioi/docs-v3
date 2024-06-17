---
title: Set Max Audio Channels Scaled
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio)

Sets the max number of voices (also known as "channels") dynamically by percentage. E.g. if you want to temporarily
reduce voice count by 50%, use 0.50. Later, you can return to the original max voice count by using 1.0.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| real | Max Channel Count Scale | The percentage of the original voice count to set the max number of voices to |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

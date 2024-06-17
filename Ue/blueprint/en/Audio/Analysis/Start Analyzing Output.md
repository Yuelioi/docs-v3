---
title: Start Analyzing Output
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Audio](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio) > [Analysis](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Audio/Analysis)

Start spectrum analysis of the audio output. By leaving the Submix To Analyze blank, you can analyze the master output of the game.

Target is Audio Mixer Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Submix to Analyze |  |
| enum | FFTSize |  |
| enum | Interpolation Method |  |
| enum | Window Type |  |
| real | Hop Size |  |
| enum | Spectrum Type |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

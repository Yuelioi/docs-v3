---
title: Get Beat Progress Percent
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Quantization](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Quantization)

Returns the current progress until the next occurrence of the provided musical duration as a float value from 0 (previous beat) to 1 (next beat).
This is useful for indexing into curves to animate parameters to musical time.
Ms and Phase offsets are combined internally.

Target is Quartz Clock Handle

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| enum | Quantization Boundary |  |
| real | Phase Offset |  |
| real | Ms Offset |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| real | Return Value | Returns the current progress until the next occurrence of the provided musical duration as a float value from 0 (previous beat) to 1 (next beat).This is useful for indexing into curves to animate parameters to musical time.Ms and Phase offsets are combined internally. |

---
title: Is Speech Muted
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Slate Screen Reader](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SlateScreenReader)

Returns true if text to speech for a screen reader user is muted. Otherwise false is returned.
If the provided user Id doesn't exist, false will be returned.

Target is Slate Screen Reader Engine Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| integer | Screen Reader User Id | The screen reader user Id to check if text to speech is muted. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value |  |

---
title: Evaluate Data Registry Curve
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataRegistry)

Attempts to evaluate a curve stored in a DataRegistry cache using a specific input value

Target is Data Registry Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Item Id | Item identifier to lookup in cache |
| real | Input Value | Time/level/parameter input value used to evaluate curve at certain position |
| real | Default Value | Value to use if no curve found or input is outside acceptable range |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Found | Found the row successfully. |
| exec | Not Found | Failed to find the row. |
| real | Out Value | Result will be replaced with evaluated value, or default if that fails |

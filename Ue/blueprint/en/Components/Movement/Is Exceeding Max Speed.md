---
title: Is Exceeding Max Speed
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Components](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components) > [Movement](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Components/Movement)

Returns true if the current velocity is exceeding the given max speed (usually the result of GetMaxSpeed()), within a small error tolerance.
Note that under normal circumstances updates cause by acceleration will not cause this to be true, however external forces or changes in the max speed limit
can cause the max speed to be violated.

Target is Movement Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| real | Max Speed |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | Returns true if the current velocity is exceeding the given max speed (usually the result of GetMaxSpeed()), within a small error tolerance.Note that under normal circumstances updates cause by acceleration will not cause this to be true, however external forces or changes in the max speed limitcan cause the max speed to be violated. |

---
title: FindSubobjectDataFromHandle
order: 15
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Subobject Data Subsystem](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SubobjectDataSubsystem)

Attempt to find the subobject data for a given handle. OutData will only
be valid if the function returns true.

Target is Subobject Data Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Handle | Handle of the subobject data you want to acquire |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Out Data | Reference to the subobject data to populate |
| boolean | Return Value | bool true if the data was found |

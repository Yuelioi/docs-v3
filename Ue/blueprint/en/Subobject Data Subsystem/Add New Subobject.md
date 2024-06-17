---
title: Add New Subobject
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Subobject Data Subsystem](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SubobjectDataSubsystem)

Add a new subobject as a child to the given parent object

Target is Subobject Data Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Params | Options to consider when adding this subobject |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| text | Fail Reason |  |
| struct | Return Value | FSubobjectDataHandle Handle to the newly created subobject, Invalid handle if creation failed |

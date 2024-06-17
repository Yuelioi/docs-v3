---
title: Initialize As Copy With Attribute Filter
order: 62
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [PCG](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG) > [Metadata](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG/Metadata)

Initializes the metadata from a parent metadata by copy filtered attributes only to it

Target is PCGMetadata

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Metadata to Copy | Metadata to copy from |
| name | In Filtered Attributes | Attributes to keep/exclude, can be empty. |
| int64 | In Optional Entries to Copy | Optional array that contains the keys to copy over. This array order will be respected, so it can also be used to re-order entries. If empty, copy them all. |
| enum | In Filter Mode | Filter to know if we should keep or exclude InFilteredAttributes. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

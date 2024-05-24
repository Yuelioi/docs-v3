---
display_name: Initialize with Attribute Filter
order: 65
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [PCG](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG) > [Metadata](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG/Metadata)

Initializes the metadata from a parent metadata. Copies attributes and values.

Target is PCGMetadata

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Parent | The parent metadata to use as a template, if any (can be null). |
| name | In Filtered Attributes | Optional list of attributes to exclude or include when adding the attributes from the parent. |
| enum | In Filter Mode | Defines attribute filter operation. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

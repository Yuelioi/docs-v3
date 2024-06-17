---
title: Add Attributes Filtered
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [PCG](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG) > [Metadata](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG/Metadata)

Creates missing attributes from another metadata if they are not currently present - note that this does not copy values.

Target is PCGMetadata

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Other | The other metadata to obtain a list of attributes from. |
| name | In Filtered Attributes | Optional list of attributes to exclude or include when adding the attributes. |
| enum | In Filter Mode | Defines attribute filter operation. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

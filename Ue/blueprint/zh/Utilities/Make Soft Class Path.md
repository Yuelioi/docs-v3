---
title: Make Soft Class Path
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

Builds a Soft Class Path struct from a string that contains a full /folder/packagename.class path.
For blueprint classes, this needs to point to the actual class (often with \_C) and not the blueprint editor asset

Target is Kismet System Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Path String |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Builds a Soft Class Path struct from a string that contains a full /folder/packagename.class path.For blueprint classes, this needs to point to the actual class (often with \_C) and not the blueprint editor asset |

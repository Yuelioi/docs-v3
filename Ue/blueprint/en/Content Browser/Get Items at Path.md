---
display_name: Get Items at Path
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Content Browser](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ContentBrowser)

Get the items (folders and/or files) that exist at the given virtual path.
Note: Multiple items may have the same virtual path if they are different types, or come from different data sources.

Target is Content Browser Data Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | In Path |  |
| enum | In Item Type Filter |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Get the items (folders and/or files) that exist at the given virtual path.@note Multiple items may have the same virtual path if they are different types, or come from different data sources. |

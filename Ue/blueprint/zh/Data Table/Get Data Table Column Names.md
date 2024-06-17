---
title: Get Data Table Column Names
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Data Table](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/DataTable)

Get the name of each column in this Data Table.
Note: These are always the raw property names (See: GetDataTableColumnAsString) rather than the friendly export name that would be used in a CSV/JSON export (See: GetDataTableColumnNameFromExportName).

Target is Data Table Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Table |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Out Column Names |  |

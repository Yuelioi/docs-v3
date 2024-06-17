---
title: Get Data Table Row
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities)

Attempts to retrieve a TableRow from a DataTable via it's RowName

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Data Table | Data Table Object Reference Data TableThe DataTable you want to retreive a row from |
| name | Row Name | Name Row NameThe name of the row to retrieve from the DataTable |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Row Found |  |
| exec | Row Not Found |  |
| wildcard | Out Row | Wildcard Out RowThe returned TableRow, if found |

---
title: Scripted Add Filename
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Import Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetImportData)

Add or update a filename at the specified index. If the index is greater then the number of source file,
it will add empty filenames to fill up to the specified index. The timespan and MD5 will be computed.

Target is Asset Import Data

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Path |  |
| integer | Index |  |
| string | Source File Label |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

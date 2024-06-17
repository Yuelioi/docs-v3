---
title: Get Objects
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Import Task](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetImportTask)

Get the list of imported objects.
Note that if the import was asynchronous, this will block until the results are ready.
To test whether asynchronous results are ready or not, use IsAsyncImportComplete().

Target is Asset Import Task

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | Get the list of imported objects.Note that if the import was asynchronous, this will block until the results are ready.To test whether asynchronous results are ready or not, use IsAsyncImportComplete(). |

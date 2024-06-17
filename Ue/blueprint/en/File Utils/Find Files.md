---
title: Find Files
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [File Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/FileUtils)

Finds all the files within the given directory, with optional file extension filter.

Target is Blueprint File Utils BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Directory | The absolute path to the directory to search. Ex: "C:\\UnrealEditor\\Pictures" |
| string | File Extension | If FileExtension is empty string "" then all files are found. Otherwise FileExtension can be of the form .EXT or just EXT and only files with that extension will be returned. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Found Files | All the files found that matched the optional FileExtension filter, or all files if none was specified. |
| boolean | Return Value | true if anything was found, false otherwise |

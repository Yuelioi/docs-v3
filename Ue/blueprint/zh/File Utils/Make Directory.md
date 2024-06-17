---
title: Make Directory
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [File Utils](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/FileUtils)

Makes a new directory, and optionally sub-directories

Target is Blueprint File Utils BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Path | The directory path to make |
| boolean | Create Tree | If true, the entire directory tree will be created if it doesnt exist. Otherwise only the leaft most directory will be created if possible |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the directory was created, false otherwise |

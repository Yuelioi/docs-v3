---
title: Make Standard Filename
order: 62
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Paths](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Paths)

Make fully standard "Unreal" pathname:

- Normalizes path separators \[NormalizeFilename\]
- Removes extraneous separators \[NormalizeDirectoryName, as well removing adjacent separators\]
- Collapses internal ..'s
- Makes relative to Engine\\Binaries\\ (will ALWAYS start with ......)

Target is Blueprint Paths Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | In Path |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Out Path |  |

---
title: Get Dependencies (Message)
order: 20
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Gets a list of paths to objects that are referenced by the supplied package. (On disk references ONLY)

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Package Name | the name of the package for which to gather dependencies (eg, /Game/MyFolder/MyAsset) |
| struct | Dependency Options | which kinds of dependencies to include in the output list |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Out Dependencies | a list of packages that are referenced by the package whose path is PackageName |
| boolean | Return Value |  |

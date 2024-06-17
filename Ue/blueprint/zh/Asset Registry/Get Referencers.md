---
title: Get Referencers
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Asset Registry](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AssetRegistry)

Gets a list of packages that reference the supplied package. (On disk references ONLY)

Target is Asset Registry

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| interface | Target |  |
| name | Package Name | the name of the package for which to gather dependencies (eg, /Game/MyFolder/MyAsset) |
| struct | Reference Options | which kinds of references to include in the output list |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| name | Out Referencers | a list of packages that reference the package whose path is PackageName |
| boolean | Return Value |  |

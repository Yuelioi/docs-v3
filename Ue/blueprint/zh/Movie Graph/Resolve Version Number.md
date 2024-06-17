---
title: Resolve Version Number
order: 67
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Movie Graph](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/MovieGraph)

If the version number is explicitly specified on the Output Setting node, returns that. Otherwise searches the
output directory for the highest version that already exists (and increments it by one if bGetNextVersion is
true). Returns -1 if the version could not be resolved.

Target is Movie Graph Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | In Params |  |
| boolean | Get Next Version |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | If the version number is explicitly specified on the Output Setting node, returns that. Otherwise searches theoutput directory for the highest version that already exists (and increments it by one if bGetNextVersion istrue). Returns -1 if the version could not be resolved. |

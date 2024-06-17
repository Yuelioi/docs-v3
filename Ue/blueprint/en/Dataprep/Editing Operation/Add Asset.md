---
title: Add Asset
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dataprep](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep) > [Editing Operation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep/EditingOperation)

DUplicate and add an asset to the Dataprep's and action's working set

Target is Dataprep Editing Operation

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Asset | If not null, the asset will be duplicated |
| string | Asset Name | Name of the asset to create. Name collision will be checked and fixed before naming the asset |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The asset newly created |

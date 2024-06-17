---
title: Init Write
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara Data Channel](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NiagaraDataChannel)

Call before each batch of writes to allocate the data we'll be writing to.

Target is Niagara Data Channel Writer

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Search Params |  |
| integer | Count |  |
| boolean | Visible to Game |  |
| boolean | Visible to CPU |  |
| boolean | Visible to GPU |  |
| string | Debug Source |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Call before each batch of writes to allocate the data we'll be writing to. |

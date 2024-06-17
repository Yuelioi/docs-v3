---
title: Write To Niagara Data Channel (Batch)
order: 28
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara Data Channel](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NiagaraDataChannel)

Initializes and returns the Niagara Data Channel writer to write N elements to the given data channel.

Target is Niagara Data Channel Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Channel | The channel to write to |
| struct | Search Params | Parameters used when retrieving a specific set of Data Channel Data to read or write like the islands data channel type. |
| integer | Count | The number of elements to write |
| boolean | Visible To Blueprint | If true, the data written to this data channel is visible to Blueprint and C++ logic reading from it |
| boolean | Visible To Niagara CPU | If true, the data written to this data channel is visible to Niagara CPU emitters |
| boolean | Visible To Niagara GPU | If true, the data written to this data channel is visible to Niagara GPU emitters |
| string | Debug Source | Instigator for this write, used in the debug hud to track writes to the data channel from different sources |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |

---
display_name: Read From Niagara Data Channel (Batch)
order: 8
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara Data Channel](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NiagaraDataChannel)

Initializes and returns the Niagara Data Channel reader for the given data channel.

Target is Niagara Data Channel Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Channel | The channel to read from |
| struct | Search Params | Parameters used when retrieving a specific set of Data Channel Data to read or write like the islands data channel type. |
| boolean | Read Previous Frame | True if this reader will read the previous frame's data. If false, we read the current frame. Reading the current frame allows for zero latency reads, but any data elements that are generated after this reader is used are missed. Reading the previous frame's data introduces a frame of latency but ensures we never miss any data as we have access to the whole frame. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value |  |

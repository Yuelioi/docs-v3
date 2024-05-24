---
display_name: Write To Niagara Data Channel
order: 29
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara Data Channel](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/NiagaraDataChannel)

Writes a single element to a Niagara Data Channel. The element won't be immediately visible to readers, as it needs to be processed first. The earliest point it can be read is in the next tick group.

Target is Niagara Data Channel Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Channel | The channel to write to |
| struct | Search Params | Parameters used when retrieving a specific set of Data Channel Data to read or write like the islands data channel type. |
| boolean | Visible to Blueprint | If true, the data written to this data channel is visible to Blueprint and C++ logic reading from it |
| boolean | Visible to Niagara CPU | If true, the data written to this data channel is visible to Niagara CPU emitters |
| boolean | Visible to Niagara GPU | If true, the data written to this data channel is visible to Niagara GPU emitters |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

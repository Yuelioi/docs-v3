---
display_name: Initialize As Copy
order: 63
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [PCG](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG) > [Metadata](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/PCG/Metadata)

Initializes the metadata from a parent metadata by copying all attributes to it.

Target is PCGMetadata

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Metadata to Copy | Metadata to copy from |
| int64 | In Optional Entries to Copy | Optional array that contains the keys to copy over. This array order will be respected, so it can also be used to re-order entries. If empty, copy them all. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

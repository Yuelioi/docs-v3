---
display_name: Copy Meta Data
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Level Sequence](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/LevelSequence)

Copy the specified meta data into this level sequence, overwriting any existing meta-data of the same type
Meta-data may implement the ILevelSequenceMetaData interface in order to hook into default ULevelSequence functionality.

Target is Level Sequence

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Meta Data | Existing Metadata Object that you wish to copy into this Level Sequence. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | The newly copied instance of the Metadata that now exists on this sequence. |

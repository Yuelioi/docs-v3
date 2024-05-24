---
display_name: Get Data From Collection
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover) > [Data](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover/Data)

Retrieves data from a collection, by writing to a target instance if it contains one of the matching type. Changes must be written back using AddDataToCollection.

Target is Mover Data Collection Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Collection |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Did Succeed | Flag indicating whether data was actually written to target struct instance |
| wildcard | Out Struct | The data struct instance to write to, which must be a FMoverDataStructBase sub-type |

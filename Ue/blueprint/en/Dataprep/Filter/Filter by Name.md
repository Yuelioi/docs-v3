---
display_name: Filter by Name
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Dataprep](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep) > [Filter](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Dataprep/Filter)

Filter the array based on the Object name.

Target is Datasmith Data Preparation Filter Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target Array | Array of Object to filter. The array will not change. |
| string | Name Sub String | The name to filter with. |
| enum | String Match | Contains the NameSubString OR matches with the wildcard \*? OR exactly the same value. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | The filtered list. |

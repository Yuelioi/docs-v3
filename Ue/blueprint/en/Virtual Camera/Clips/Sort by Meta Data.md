---
display_name: Sort by Meta Data
order: 22
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera) > [Clips](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera/Clips)

Sorts the assets based on their meta data's type.
Supported types: FString, int, float, FDateTime.

Target is Asset Filtering and Sorting Function Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Assets | The assets to sort |
| name | Meta Data Tag | The on which the sort is based |
| enum | Meta Data Type |  |
| enum | Sort Order | Whether to sort ascending or descending |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether it was possible to compare all the meta data successfully. |

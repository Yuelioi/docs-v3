---
display_name: Get Query Results as Locations
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [EQS](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/EQS)

Outputs an array of locations generated by the query. If the query generated Actors the the array is filled with their locations. Returns false if there is no valid result.

Target is EQS Query Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| vector | Result Locations |  |
| boolean | Return Value | Outputs an array of locations generated by the query. If the query generated Actors the the array is filled with their locations. Returns false if there is no valid result. |
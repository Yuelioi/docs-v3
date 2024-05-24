---
display_name: Move to Location
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Move to the specified location, using the vector curve (range 0 - 1) if specified, otherwise the float curve (range 0 - 1) or fallback to linear interpolation

Target is Ability Task Move to Location

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Task Instance Name |  |
| vector | Location |  |
| real | Duration |  |
| object | Optional Interpolation Curve |  |
| object | Optional Vector Interpolation Curve |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Target Location Reached |  |

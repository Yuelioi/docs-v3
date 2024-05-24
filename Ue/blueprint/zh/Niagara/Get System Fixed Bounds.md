---
display_name: Get System Fixed Bounds
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Niagara](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Niagara)

Gets the fixed bounds for the system instance.
This will return the user set fixed bounds if set, or the systems fixed bounds if set.
Note: The returned box may be invalid if no fixed bounds exist

Target is Niagara Particle System Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Gets the fixed bounds for the system instance.This will return the user set fixed bounds if set, or the systems fixed bounds if set.Note: The returned box may be invalid if no fixed bounds exist |

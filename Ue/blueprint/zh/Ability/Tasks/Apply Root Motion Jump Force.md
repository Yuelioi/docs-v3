---
display_name: Apply Root Motion Jump Force
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Apply force to character's movement

Target is Ability Task Apply Root Motion Jump Force

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Task Instance Name |  |
| rotator | Rotation |  |
| real | Distance |  |
| real | Height |  |
| real | Duration |  |
| real | Minimum Landed Trigger Time |  |
| boolean | Finish on Landed |  |
| enum | Velocity on Finish Mode |  |
| vector | Set Velocity on Finish |  |
| real | Clamp Velocity on Finish |  |
| object | Path Offset Curve |  |
| object | Time Mapping Curve |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | On Finish |  |
| exec | On Landed |  |

---
display_name: Wait Target Data Using Actor
order: 40
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Uses specified target actor and waits for it to return valid data or to be canceled.

Target is Ability Task Wait Target Data

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| name | Task Instance Name |  |
| enum | Confirmation Type |  |
| object | Target Actor |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Task |  |
| exec | Valid Data |  |
| exec | Cancelled |  |
| struct | Data |  |

---
display_name: Wait Gameplay Tag Count Changed on Actor
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until the specified gameplay tag count changes on Target Actor's ability component
If used in an ability graph, this async action will wait even after activation ends. It's recommended to use WaitGameplayTagCountChange instead.

Target is Ability Async Wait Gameplay Tag Count Changed

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target Actor |  |
| struct | Tag |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Action |  |
| exec | Tag Count Changed |  |
| integer | Tag Count |  |

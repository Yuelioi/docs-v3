---
display_name: Wait for Attribute Changed
order: 49
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Ability](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability) > [Tasks](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Ability/Tasks)

Wait until the specified gameplay attribute is changed on a target ability system component
It will keep listening as long as OnlyTriggerOnce = false
If used in an ability graph, this async action will wait even after activation ends. It's recommended to use WaitForAttributeChange instead.

Target is Ability Async Wait Attribute Changed

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Attribute |  |
| object | Target Actor |  |
| boolean | Only Trigger Once |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Async Action |  |
| exec | Changed |  |
| real | New Value |  |
| real | Old Value |  |

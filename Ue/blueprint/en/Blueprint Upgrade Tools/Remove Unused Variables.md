---
display_name: Remove Unused Variables
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Blueprint Upgrade Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/BlueprintUpgradeTools)

Deletes any unused blueprint created variables the given blueprint.
An Unused variable is any BP variable that is not referenced in any
blueprint graphs

Target is Blueprint Editor Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Blueprint | Blueprint that you would like to remove variables from |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| integer | Return Value | Number of variables removed |

---
display_name: Get Blueprint Asset
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Blueprint Upgrade Tools](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/BlueprintUpgradeTools)

Casts the provided Object to a Blueprint - the root asset type of a blueprint asset. Note
that the blueprint asset itself is editor only and not present in cooked assets.

Target is Blueprint Editor Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Object | The object we need to get the UBlueprint from |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | UBlueprint\* The blueprint type of the given object, nullptr if the object is not a blueprint. |

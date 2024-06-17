---
title: Has All Matching Gameplay Tags
order: 16
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Tags](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayTags)

Check if the asset has gameplay tags that matches against all of the specified tags (expands to include parents of asset tags)

Target is Gameplay Tag Asset Interface

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| interface | Target |  |
| struct | Tag Container | Tag container to check for a match |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | True if the asset has matches all of the gameplay tags, will be true if container is empty |

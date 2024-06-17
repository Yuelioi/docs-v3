---
title: Has Tag
order: 23
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Tags](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayTags)

Check if the tag container has the specified tag

Target is Blueprint Gameplay Tag Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Tag Container | Container to check for the tag |
| struct | Tag | Tag to check for in the container |
| boolean | Exact Match | If true, the tag has to be exactly present, if false then TagContainer will include it's parent tags while matching |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | True if the container has the specified tag, false if it does not |

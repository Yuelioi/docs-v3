---
title: Has All Tags
order: 17
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Gameplay Tags](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameplayTags)

Check if the specified tag container has ALL of the tags in the other container

Target is Blueprint Gameplay Tag Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Tag Container | Container to check if it matches all of the tags in the other container |
| struct | Other Container | Container to check against. If this is empty, the check will succeed |
| boolean | Exact Match | If true, the tag has to be exactly present, if false then TagContainer will include it's parent tags while matching |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| boolean | Return Value | True if the container has ALL of the tags in the other container |

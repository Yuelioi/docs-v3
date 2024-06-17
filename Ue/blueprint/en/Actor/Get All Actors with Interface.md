---
title: Get All Actors with Interface
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Actor](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Actor)

Find all Actors in the world with the specified interface.
This is a slow operation, use with caution e.g. do not use every frame.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| class | Interface | Interface to find. Must be specified or result array will be empty. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Out Actors | Output array of Actors of the specified interface. |

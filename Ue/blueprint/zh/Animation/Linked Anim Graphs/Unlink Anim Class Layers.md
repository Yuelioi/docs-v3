---
title: Unlink Anim Class Layers
order: 12
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Animation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation) > [Linked Anim Graphs](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Animation/LinkedAnimGraphs)

Runs through all layer nodes, attempting to find layer nodes that are currently running the specified class, then resets each to its default value.
State sharing rules are as with SetLayerOverlay.
If InClass is null, does nothing.

Target is Anim Instance

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | In Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

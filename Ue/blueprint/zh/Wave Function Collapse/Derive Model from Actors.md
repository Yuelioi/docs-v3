---
title: Derive Model from Actors
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Wave Function Collapse](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WaveFunctionCollapse)

Derive constraints from a given layout of actors and append them to a model

Target is Wave Function Collapse BPLibrary

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Actors | array of actors to evaluate |
| object | WFCModel | to add constraints to |
| real | Tile Size | distance between tiles |
| boolean | Is Border Empty Option | should the border be considered EmptyOption |
| boolean | Is Min ZFloor Option | should the minimum Z actors be considered floor options (nothing can go below it) |
| boolean | Use Uniform Weight Distribution |  |
| boolean | Auto Derive ZAxis Rotation Constraints | should it auto derive z-axis rotational variants |
| struct | Spawn Exclusion Assets | assets to exclude when spawning |
| struct | Ignore Rotation Assets | assets to ignore rotation variants |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

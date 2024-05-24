---
display_name: Observe
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [WFCFunctions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WFCFunctions)

Observation phase:
This process randomly selects one tile from minimum entropy tiles
then randomly selects a valid option for that tile

Target is Wave Function Collapse Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Random Seed |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Tiles | Array of tiles (by ref) |
| integer | Remaining Tiles | Array of remaining tile indices. Semi-sorted: Min Entropy tiles at the front, the rest remains unsorted (by ref) |
| integer | Observation Queue | Array to store tiles that need to be checked whether remaining options are affected during propagation phase (by ref) |
| boolean | Return Value |  |

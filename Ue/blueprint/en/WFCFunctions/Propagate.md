---
display_name: Propagate
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [WFCFunctions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WFCFunctions)

Propagation phase:
This process checks if the selection made during the observation is valid by checking constraint validity with neighboring tiles.
Neighboring tiles may reduce their remaining options to include only valid options.
If the remaining options of a tile were modified, the neighboring tiles of the modified tile will be added to a queue.
During this process, if any contradiction (a tile with zero remaining options) is encountered, the current solve will fail.

Target is Wave Function Collapse Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Tiles | Array of tiles (by ref) |
| integer | Remaining Tiles | Array of remaining tile indices. Semi-sorted: Min Entropy tiles at the front, the rest remains unsorted (by ref) |
| integer | Observation Queue | Array to store tiles that need to be checked whether remaining options are affected (by ref) |
| integer | Propagation Count | Counter for propagation passes |
| boolean | Return Value |  |

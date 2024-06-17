---
title: Observation Propagation
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [WFCFunctions](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/WFCFunctions)

Recursive Observation and Propagation cycle

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
| integer | Remaining Tiles | Array of remaining tile indices (by ref) |
| integer | Observation Queue | Array to store tiles that need to be checked whether remaining options are affected (by ref) |
| boolean | Return Value |  |

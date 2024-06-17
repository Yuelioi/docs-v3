---
title: Try Safe Move Updated Component
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Mover](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Mover)

Attempts to move a component and resolve any penetration issues with the proposed move Delta

Target is Movement Utils

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Updated Component |  |
| object | Updated Primitive |  |
| vector | Delta |  |
| struct | New Rotation |  |
| boolean | Sweep |  |
| enum | Teleport |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| struct | Out Hit |  |
| struct | Move Record |  |
| boolean | Return Value | Attempts to move a component and resolve any penetration issues with the proposed move Delta |

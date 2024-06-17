---
title: Set Max Simultaneous Tile Generation Jobs Count
order: 39
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Navigation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Navigation)

will limit the number of simultaneously running navmesh tile generation jobs to specified number.

Target is Navigation System V1

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| integer | Max Number Of Jobs | gets trimmed to be at least 1. You cannot use this function to pause navmesh generation |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

---
title: Register Navigation Invoker
order: 31
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [AI](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI) > [Navigation](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/AI/Navigation)

Registers given actor as a "navigation enforcer" which means navigation system will
make sure navigation is being generated in specified radius around it.
Note:: you need NavigationSystem's GenerateNavigationOnlyAroundNavigationInvokers to be set to true
to take advantage of this feature

Target is Navigation System V1

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Invoker |  |
| real | Tile Generation Radius |  |
| real | Tile Removal Radius |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

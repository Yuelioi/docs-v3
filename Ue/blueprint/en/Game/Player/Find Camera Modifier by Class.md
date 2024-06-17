---
title: Find Camera Modifier by Class
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game) > [Player](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Game/Player)

Returns camera modifier for this camera of the given class, if it exists.
Exact class match only. If there are multiple modifiers of the same class, the first one is returned.

Target is Player Camera Manager

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| class | Modifier Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Returns camera modifier for this camera of the given class, if it exists.Exact class match only. If there are multiple modifiers of the same class, the first one is returned. |

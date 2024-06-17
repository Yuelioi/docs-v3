---
title: Remove Console Variable
order: 94
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Settings](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Settings)

Removes the console variable override with the specified name. If more than one with the same name exists, the
last one will be removed. Returns true if at least one console variable was removed, else false.

Target is Movie Pipeline Console Variable Setting

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Name |  |
| boolean | Remove All Instances | Remove all console variables overrides with the given name (not just the last one) |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value |  |

---
title: Get Key Value
order: 2
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Game Options](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/GameOptions)

Break up a key=value pair into its key and value.

Target is Gameplay Statics

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | Pair | The string containing a pair to split apart. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Key | (out) Key portion of Pair. If no = in string will be the same as Pair. |
| string | Value | (out) Value portion of Pair. If no = in string will be empty. |

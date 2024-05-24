---
display_name: Get All Render Grid Assets
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Render Grid](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RenderGrid)

Returns all render grid assets that currently exist in the project (on disk and in memory).
Will load the render grid assets in that are currently unloaded.

This is a slow operation, so avoid doing this every tick.

Target is Render Grid Developer Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Returns all render grid assets that currently exist in the project (on disk and in memory).Will load the render grid assets in that are currently unloaded.This is a slow operation, so avoid doing this every tick. |

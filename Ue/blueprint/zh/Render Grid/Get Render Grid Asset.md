---
title: Get Render Grid Asset
order: 24
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Render Grid](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RenderGrid)

Returns the given render grid asset that exists at the given object path (whether it's on disk or in memory).
Will load the render grid asset if it's currently unloaded.

This is a potentially slow operation, so avoid doing this every tick.

Target is Render Grid Developer Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Object Path |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Return Value | Returns the given render grid asset that exists at the given object path (whether it's on disk or in memory).Will load the render grid asset if it's currently unloaded.This is a potentially slow operation, so avoid doing this every tick. |

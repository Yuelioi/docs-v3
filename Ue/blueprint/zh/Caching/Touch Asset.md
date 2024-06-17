---
title: Touch Asset
order: 14
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Caching](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Caching)

Marks the provided asset as being used at this point, optionally adding a specific referencer.
This is useful because the asset cache will always prioritize retaining the most recently used assets

Target is USD Asset Cache

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | Asset |  |
| object | Referencer |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Marks the provided asset as being used at this point, optionally adding a specific referencer.This is useful because the asset cache will always prioritize retaining the most recently used assets |

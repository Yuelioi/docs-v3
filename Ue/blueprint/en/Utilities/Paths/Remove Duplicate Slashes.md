---
title: Remove Duplicate Slashes
order: 77
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Paths](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Paths)

Removes duplicate slashes in paths.
Assumes all slashes have been converted to TEXT('/').
For example, takes the string:
BaseDirectory/SomeDirectory//SomeOtherDirectory////Filename.ext
and converts it to:
BaseDirectory/SomeDirectory/SomeOtherDirectory/Filename.ext

Target is Blueprint Paths Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | In Path |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Out Path |  |

---
title: Collapse Relative Directories
order: 7
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Utilities](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities) > [Paths](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Utilities/Paths)

Takes a fully pathed string and eliminates relative pathing (eg: annihilates ".." with the adjacent directory).
Assumes all slashes have been converted to TEXT('/').
For example, takes the string:
BaseDirectory/SomeDirectory/../SomeOtherDirectory/Filename.ext
and converts it to:
BaseDirectory/SomeOtherDirectory/Filename.ext

Target is Blueprint Paths Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| string | In Path |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Out Path |  |
| boolean | Return Value | Takes a fully pathed string and eliminates relative pathing (eg: annihilates ".." with the adjacent directory).Assumes all slashes have been converted to TEXT('/').For example, takes the string:BaseDirectory/SomeDirectory/../SomeOtherDirectory/Filename.extand converts it to:BaseDirectory/SomeOtherDirectory/Filename.ext |

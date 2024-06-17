---
title: Add Console Variable
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Settings](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Settings)

Adds a console variable override with the given name and value, and will add a duplicate if one with the provided
name already exists. Returns true if the operation was successful, else false.
See: AddOrUpdateConsoleVariable()

Target is Movie Pipeline Console Variable Setting

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Name |  |
| real | Value |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Adds a console variable override with the given name and value, and will add a duplicate if one with the providedname already exists. Returns true if the operation was successful, else false.@see AddOrUpdateConsoleVariable() |

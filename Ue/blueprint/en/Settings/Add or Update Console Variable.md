---
title: Add or Update Console Variable
order: 9
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Settings](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Settings)

Adds a console variable override with the given name and value if one does not already exist. If the console
variable with the given name already exists, its value will be updated (the last one will be updated if there are
duplicates with the same name). Returns true if the operation was successful, else false.
See: AddConsoleVariable()

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
| boolean | Return Value | Adds a console variable override with the given name and value if one does not already exist. If the consolevariable with the given name already exists, its value will be updated (the last one will be updated if there areduplicates with the same name). Returns true if the operation was successful, else false.@see AddConsoleVariable() |

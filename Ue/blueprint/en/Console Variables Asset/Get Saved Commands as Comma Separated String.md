---
title: Get Saved Commands as Comma Separated String
order: 6
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Console Variables Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ConsoleVariablesAsset)

Returns the saved list of console variables as a concatenated comma-separated string. Useful for passing commands and variables to a command line.

Target is Console Variables Asset

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| boolean | Only Include Checked | If true, only commands and variables with a Checked checkstate in the Console Variables Editor UI will be included. Otherwise, all will be included. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value |  |

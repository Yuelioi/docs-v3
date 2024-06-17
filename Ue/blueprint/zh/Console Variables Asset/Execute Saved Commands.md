---
title: Execute Saved Commands
order: 3
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Console Variables Asset](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/ConsoleVariablesAsset)

Executes all saved commands in this asset, optionally only including those with a Checked checkstate in the UI.

Target is Console Variables Asset

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| boolean | Only Include Checked | If true, only commands and variables with a Checked checkstate in the Console Variables Editor UI will be included. Otherwise, all will be included. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |

---
title: Execute Python Command (Advanced)
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Python](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Python) > [Execution](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Python/Execution)

Execute the given Python command.

Target is Python Script Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| string | Python Command | The command to run. This may be literal Python code, or a file (with optional arguments) that you want to run. |
| enum | Execution Mode | Controls the mode used to execute the command. |
| enum | File Execution Scope | Controls the scope used when executing Python files. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| string | Command Result | The result of running the command. On success, for EvaluateStatement mode this will be the actual result of running the command, and will be None in all other cases. On failure, this will be the error information (typically a Python exception trace). |
| struct | Log Output | The log output captured while running the command. |
| boolean | Return Value | true if the command ran successfully, false if there were errors. |

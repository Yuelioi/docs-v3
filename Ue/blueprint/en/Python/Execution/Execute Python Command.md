---
display_name: Execute Python Command
order: 2
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

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | true if the command ran successfully, false if there were errors (the output log will show the errors). |

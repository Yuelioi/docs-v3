---
display_name: Register Command Checked
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Editor Scripting](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting) > [Commands](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/EditorScripting/Commands)

Registers a command within the given context and set.
The set must be registered beforehand.

Target is UICommands Scripting Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| struct | Command Info | The command infos such as name, label, description and input chord. |
| delegate | On Execute Command | The delegate to be executed for handling this command. |
| delegate | On Can Execute Command | The delegate to be executed for checking if this command can be executed. |
| boolean | Override Existing | Whether existing command with matching context, set and name should be overriden |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Whether the command was successfully registered |

---
display_name: Bind Pin to Variable
order: 34
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMController](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMController)

Binds a pin to a variable (or removes the binding given NAME_None)
This causes a PinBoundVariableChanged modified event.

Target is Rig VMController

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | In Pin Path |  |
| string | In New Bound Variable Path |  |
| boolean | Setup Undo Redo |  |
| boolean | Print Python Command |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Binds a pin to a variable (or removes the binding given NAME_None)This causes a PinBoundVariableChanged modified event. |

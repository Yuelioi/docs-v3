---
display_name: Get Variable Assignment Enable State
order: 18
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Experimental](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Experimental)

Gets the enable state of the variable assignment for the provided graph variable. The enable state is provided
via bOutIsEnabled. Returns true if an enable state was set on the variable and bOutIsEnabled was changed, else false.

Target is Movie Job Variable Assignment Container

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| object | In Graph Variable |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Out Is Enabled |  |
| boolean | Return Value | Gets the enable state of the variable assignment for the provided graph variable. The enable state is providedvia bOutIsEnabled. Returns true if an enable state was set on the variable and bOutIsEnabled was changed, else false. |

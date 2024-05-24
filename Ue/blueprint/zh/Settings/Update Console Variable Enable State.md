---
display_name: Update Console Variable Enable State
order: 4
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Settings](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Settings)

Updates the enable state of the console variable override with the provided name. If there are duplicate cvars
with the same name, the last one with the provided name will be updated. Returns true if the operation was
successful, else false.

Target is Movie Pipeline Console Variable Setting

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| string | Name |  |
| boolean | Is Enabled |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Return Value | Updates the enable state of the console variable override with the provided name. If there are duplicate cvarswith the same name, the last one with the provided name will be updated. Returns true if the operation wassuccessful, else false. |

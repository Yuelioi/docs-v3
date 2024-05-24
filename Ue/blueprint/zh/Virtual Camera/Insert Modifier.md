---
display_name: Insert Modifier
order: 11
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera_1)

Insert a modifier to the stack with a given name and index.
If that name is already in use then the modifier will not be added.
The index must be between zero and the number of existing modifiers inclusive
Returns the created modifier if the Add succeeded.

Target is VCam Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name |  |
| integer | Index |  |
| class | Modifier Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Created Modifier |  |
| boolean | Success | Insert a modifier to the stack with a given name and index.If that name is already in use then the modifier will not be added.The index must be between zero and the number of existing modifiers inclusiveReturns the created modifier if the Add succeeded. |

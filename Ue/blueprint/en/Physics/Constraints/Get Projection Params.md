---
display_name: Get Projection Params
order: 32
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics) > [Constraints](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics/Constraints)

Gets projection parameters of the constraint

Target is Constraint Instance Blueprint Library

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| struct | Accessor | Constraint accessor to query |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| boolean | Enable Projection | true to enable projection |
| real | Projection Linear Alpha | how much linear projection to apply in \[0,1\] range |
| real | Projection Angular Alpha | how much angular projection to apply in \[0,1\] range |

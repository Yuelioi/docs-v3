---
title: Add Modifier
order: 1
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Virtual Camera](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/VirtualCamera_1)

Add a modifier to the stack with a given name.
If that name is already in use then the modifier will not be added.
Returns the created modifier if the Add succeeded

Target is VCam Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| exec | In |  |
| object | Target |  |
| name | Name |  |
| class | Modifier Class |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| exec | Out |  |
| object | Created Modifier |  |
| boolean | Success | Add a modifier to the stack with a given name.If that name is already in use then the modifier will not be added.Returns the created modifier if the Add succeeded |

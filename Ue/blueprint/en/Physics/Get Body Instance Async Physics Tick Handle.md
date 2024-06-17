---
title: Get Body Instance Async Physics Tick Handle
order: 65
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Physics](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/Physics)

Returns BodyInstanceAsyncPhysicsTickHandle of the component. For use in the Async Physics Tick event

Target is Primitive Component

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| name | Bone Name | Used to get body associated with specific bone. NAME_None automatically gets the root most body |
| boolean | Get Welded | If the component has been welded to another component and bGetWelded is true we return the single welded BodyInstance that is used in the simulation |
| integer | Index | Index used in Components with multiple body instances |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| struct | Return Value | Returns the BodyInstanceAsyncPhysicsTickHandle based on various states (does component have multiple bodies? Is the body welded to another body?) |

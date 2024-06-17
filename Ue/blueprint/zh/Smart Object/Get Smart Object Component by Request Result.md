---
title: Get Smart Object Component by Request Result
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Smart Object](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/SmartObject)

Returns the component associated to the given request result
In some scenarios the component may no longer exist
but its smart object data could (e.g. streaming)

Target is Smart Object Subsystem

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| struct | Result | A request result returned by any of the Find methods . |
| enum | Try Spawn Actor if Dehydrated | Indicates if the subsystem should try to spawn the actor/component associated to the smartobject if it is currently owned by an instanced actor. |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| object | Return Value | A pointer to the USmartObjectComponent\* associated to the handle. |

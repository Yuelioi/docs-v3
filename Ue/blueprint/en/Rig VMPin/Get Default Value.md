---
title: Get Default Value
order: 10
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMPin](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMPin)

Returns the default value of the Pin as a string.
Note that this value is computed based on the Pin's
SubPins - so for example for a FVector typed Pin
the default value is actually composed out of the
default values of the X, Y and Z SubPins.

Target is Rig VMPin

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | Returns the default value of the Pin as a string.Note that this value is computed based on the Pin'sSubPins - so for example for a FVector typed Pinthe default value is actually composed out of thedefault values of the X, Y and Z SubPins. |

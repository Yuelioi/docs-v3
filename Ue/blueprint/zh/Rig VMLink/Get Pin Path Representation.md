---
title: Get Pin Path Representation
order: 5
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMLink](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMLink)

Returns a string representation of the Link,
for example: "NodeA.Color.R -> NodeB.Translation.X"
note: can be split again using SplitPinPathRepresentation

Target is Rig VMLink

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | Returns a string representation of the Link,for example: "NodeA.Color.R -> NodeB.Translation.X"note: can be split again using SplitPinPathRepresentation |

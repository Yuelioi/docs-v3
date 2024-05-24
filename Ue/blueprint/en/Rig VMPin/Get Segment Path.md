---
display_name: Get Segment Path
order: 27
---
## Navigation

[Unreal Engine Blueprint API Reference](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI) > [Rig VMPin](https://dev.epicgames.com/documentation/en-us/unreal-engine/BlueprintAPI/RigVMPin)

Returns a . separated path containing all names of the pin within its main
memory owner / storage. This is typically used to create an offset pointer
within memory (FRigVMRegisterOffset).
So for example for a PinPath such as "Node.Transform.Translation.X" the
corresponding SegmentPath is "Translation.X", since the transform is the
storage / memory.

Target is Rig VMPin

## Inputs

| Type | Name | Description |
| --- | --- | --- |
| object | Target |  |
| boolean | Include Root Pin |  |

## Outputs

| Type | Name | Description |
| --- | --- | --- |
| string | Return Value | Returns a . separated path containing all names of the pin within its mainmemory owner / storage. This is typically used to create an offset pointerwithin memory (FRigVMRegisterOffset).So for example for a PinPath such as "Node.Transform.Translation.X" thecorresponding SegmentPath is "Translation.X", since the transform is thestorage / memory. |
